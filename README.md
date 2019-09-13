## _Jeg håber du har lyst til at smage, mine eksemplariske (HJEMMELAVEDE) frysepizzaer, det er tanken med Lørdags menuen, håber det er tilfredsstillende i blokken ._ 
![Image of Patricks Køkken](https://media0.giphy.com/media/iJa6kOfJ3qN7a/giphy.webp?cid=790b7611ece889afc6c8deeb07e25a75b7078ce7e00563ae&rid=giphy.webp)

## Welcome to Pallegrøns Homepage!

_Greetings y'all, welcome to my progress, practising Github page development_

### Patrick M. Grønvold - GitHub Pages
# About me.

### My name is Patrick. I am 25 years old and lives in Denmark.
**I love coffee and programming, how ever, I am a newbie at programming, PRO at drinking coffee. Dayli activites of my life, includes, fitness, family, netflix. For a living I do commercial flight arrivals and departures.**

![Image of me drinking coffe, while writing codes](https://media1.giphy.com/media/7srpeY4TZMrO8/200w.webp?cid=790b761135707c2f51b45c96061aa15e14621992e7bcf7a9&rid=200w.webp)
_**<-----Motivation** Meh, the real reason I decided to study computer science, is due to my inner motivation. 
For me, studying this topic, doesn't feel like "studying"(yet), which kinda drives me._

_It has been a long wanted replacement for my earlier hobbies and for many years I've been self practising my skills in a related matter, (the kind I felt was possible, without a teacher or fellow students to push me past the blockades of learning).
The kind of work I have experience with, are material and editing designs, PC Hardware knowledge as well as building them together into working PC. Apart from this, I feel very confident when doing cable manage ment and RGB designs._

### _My Own Build (Clickable Vid)_
[![](http://img.youtube.com/vi/Pk2hVpZywks/0.jpg)](http://www.youtube.com/watch?v=Pk2hVpZywks "Setup")


```markdown

import java.util.Scanner;
/**
 * Developed by Patrick Grønvold (patr6996@edu.easj.dk)
 * Zealand / www.zealand.dk
 * 2019-06-09
 */

//class (Main) starting point
public class MyClass {
  //psvm - public static void main
  public static void main(String[ ] args)
  {
    {
      String name = "Patrick";
      int age = 25;
      double weight = 92.5;
      char skilllevel = 'A';
    }
    // sout = System.out.println
    System.out.println("Hello World, this is my first project");

    System.out.println("Nu har jeg lært at system printe");

    //Print uden linjeskift.
    System.out.print("Printer ");
    System.out.print("uden ");
    System.out.print("linjeskift ");

    //Input fra brugeren
    Scanner s = new Scanner(System.in);
    System.out.println("skriv dit input: ");
    String input = s.next();
    System.out.println("Du har skrevet " + input);
  }
}

```
#### _Some beginner code_

```markdown

public class Main {
    public static void main(String[] args) {
        Bodytype P1 = new Bodytype();
        Bodytype P2 = new Bodytype();
        Bodytype P3 = new Bodytype();


        P1.setName("Lisa");
        P2.setName("Patrick");
        P3.setName("Simon");

        P1.setLastName("Pedersen");
        P2.setLastName("Grønvold");
        P3.setLastName("Gove");

        P1.setAge(29);
        P2.setAge(25);
        P3.setAge(20);

        P1.setHeight(168);
        P2.setHeight(189);
        P3.setHeight(180);

        P1.setWeight(49);
        P2.setWeight(55);
        P3.setWeight(95);

        P1.setActivityPerWeek(2);
        P2.setActivityPerWeek(4);
        P3.setActivityPerWeek(3);



        System.out.println("Deltagere i Test er" + " " + P1.getName() + " , " + P2.getName() + " og " + P3.getName());

        System.out.println("Lisa's Data" + " " + P1.getName() + " " + P1.getLastName() + " " + "Alder" + " " + P1.getAge() + " " +   "Højde" + " " + P1.getHeight() +" " + "Vægt" + " " + P1.getWeight() + " " + "Aktivitets niveau" + " " + P1.getActivityPerWeek() );
        System.out.println("Patricks Data" + " " + P2.getName() + " " + P2.getLastName() + " " + "Alder" + " " + P2.getAge() + " " + "Højde" + " " + P2.getHeight() +" " + "Vægt" + " " + P2.getWeight() + " " + "Aktivitets niveau" + " " + P2.getActivityPerWeek()  );
        System.out.println("Simons fulde navn er" + " " + P3.getName() + " " + P3.getLastName() + " " + "Alder" + " " + P3.getAge() + " " + "Højde" + " " + P3.getHeight() +" " + "Vægt" + " " + P3.getWeight() + " " + "Aktivitets niveau" + " " + P3.getActivityPerWeek() );

        int averageAge = (P1.getAge() + P2.getAge() + P3.getAge())/3;
        double averageHeight = (P1.getHeight() + P2.getHeight() + P3.getHeight())/3;
        double averageWeight = (P1.getWeight() + P2.getWeight() + P3.getWeight())/3;
        int averageActivity = (P1.getActivityPerWeek() + P2.getActivityPerWeek() + P3.getActivityPerWeek())/3;

        System.out.println("Average age is" + " " + averageAge);
        System.out.println("Average weight is" + " " + averageWeight);
        System.out.println("Average height is" + " " + averageHeight);
        System.out.println("Average Activity per. week is" + " " + averageActivity);


    }
}

public class Bodytype {

    String name;
    String lastName;
    int age;
    double height;
    double  weight;
    int activityPerWeek;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public String getLastName() {
        return lastName;
    }

    public void setLastName(String lastName) {
        this.lastName = lastName;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }

    public double getHeight() {
        return height;
    }

    public void setHeight(double height) {
        this.height = height;
    }

    public double getWeight() {
        return weight;
    }

    public void setWeight(double weight) {
        this.weight = weight;
    }

    public int getActivityPerWeek() {
        return activityPerWeek;
    }

    public void setActivityPerWeek(int activityPerWeek) {
        this.activityPerWeek = activityPerWeek;
    }
}

```



#### SOMETHING VERY IMPORTANT 4 YOU 2 KNOW
**Soon to come, is my birthday (_October Child_) and that is of course followed by a wishlist.**

- **_PC Artboard_** 

- **_Adobe package_** 

- **_More TIME :D_** 

![Image of Tegnetavle](https://animaster.com/wp-content/uploads/2018/02/after-10-12-art-design-college.jpg)
![Image of ADOBE](https://static.adweek.com/adweek.com-prod/wp-content/uploads/2017/03/adobe-sensei-CONTENT-20171.jpg)
![Image of More Time](https://images.fineartamerica.com/images-medium-large/grim-reaper-and-clock-granger.jpg)
