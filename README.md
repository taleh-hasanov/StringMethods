# StringMethods
//EasyWay
import java.util.Scanner;

public class StringMethods {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("add to text");

        String s = sc.nextLine();
        int i = s.length();
        System.out.println("length= "+ i);


        char c2 = s.charAt(s.length()-2);
        System.out.println("last symbol= "+c2);

       String substring = s.substring(1,3);
        System.out.println("substring= "+ substring);

        boolean b = s.contains("har");
        System.out.println("contains= "+ b);

        boolean b2 = s.equals("Java Language");
        System.out.println("equals= "+ b2);

        boolean b22 = s.equalsIgnoreCase("jAVA lAnGUAGE");
        System.out.println("equals ignore case ="+b22);

        boolean b3 = s.isEmpty();
        System.out.println("is empty= "+ b3);

        boolean b4 = s.startsWith("Java");
        System.out.println("starts with = "+b4);

        boolean b5 = s.endsWith("ing");
        System.out.println("ends with ="+ b5);

        String ss = s.trim();
        System.out.println("trim="+ss);


        String lower = s.toLowerCase();
        System.out.println("lower="+lower);

        String upper = s.toUpperCase();
        System.out.println("upper="+upper);

        int index = s.indexOf("LAN");
        System.out.println("index of LAN="+index);

        int lastindex = s.lastIndexOf("A");
        System.out.println("lastindex of A="+ lastindex);

        String repo = s.replace ("Java", "JAVALIN");
        System.out.println("replace Java with JAVALIN ="+ repo);
        
    }

}
