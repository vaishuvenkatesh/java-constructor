/* java-constructor
java constructors*/

public class Main{
    int Rollno;
    String Name;
    String Place;
    long Phoneno;
    public Main(int rollnum, String name, String place, long phoneno){
        Rollno= rollnum;
        Name = name;
        Place = place;
        Phoneno = phoneno;
    }
    public static void main(String[]args){
        Main myObj = new Main(59, "vaishu", "Krishnagiri", 6383229515L);
        System.out.print(myObj.Name+ " "+myObj.Name+ " "+myObj.Place+" "+myObj.Phoneno);
        
        
        
    }
        
        
    }
/*ouput
59 vaishu Krishnagiri 6383229515*/
