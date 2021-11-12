public class wrapperlab {
    public static void main(String args[])
    {
        Integer obj=20;//automatic boxing
        int obj3=obj;//automatic unboxing
        Integer obj1=Integer.valueOf(60);//boxing
        Integer obj2=Integer.valueOf(60);//boxing
        System.out.println(obj1.equals(obj2));
        int a=obj.intValue();//unboxing
    }
    
}
