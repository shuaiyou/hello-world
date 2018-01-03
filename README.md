# hello-world
just another repository
Edit here,I like Node,js and Cofzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz
edittest的修改，将其合并到master中




readme.md




public static void main(String [] args){
  String s="";
  JSONObject jsonObject=new JSONObject(s);
  JSONArray jsonArray=jsonObject.getJSONArray("data");
  for(int i=0;i<jsonArray.length();i++){
  JSONObject object=jsonArray.getJSONObject(i);
  JSONArray array=object.getJSONArray("logistics");
  for(int j=0;j<array.length;j++){
      JSONObject obj=array.getJSONObject("log");
      JSONArray ary=obj.getJSONArray("sj");
      for(int x=0;x<ary.length();x++){
        
      }
  }
  }
}
