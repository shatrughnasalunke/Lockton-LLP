# Lockton-LLP

Public virtual class CustomerAPI  {

      public visrtual static void getDetails() {
         
          System.debug('get Name');
      }
      public virtual stataic void  set Detailsm() {
      
         System.debug('Set Name');
      }
      //Last modified by shatrughna Slaunke
      private void setName(String Name) {
         This.Name= Name;
         System.debug();
      }
    public CustomerAPI ()  {
    
         System.debug('This is constructor');
    }   
    System.debug('I have done my changes');
    public static  String SetName() {
      System.debug('Shatrughna Salunke');
    }
}



