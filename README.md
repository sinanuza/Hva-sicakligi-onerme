# Hva-sicakligi-onerme
www.patika.dev onerme

*********

        import javax.swing.plaf.synth.SynthLookAndFeel;
        import java.util.Scanner;

        public class Onerme {
        public static void main(String[] args) {
        int heat;
        System.out.println("Hava sicakligini giriniz:");
        Scanner input=new Scanner(System.in);
        heat=input.nextInt();
        //Sıcaklık 5'dan küçük ise "Kayak" yapmayı öner.
        //Sıcaklık 5 ve 15 arasında ise "Sinema" etkinliğini öner.
        //Sıcaklık 15 ve 25 arasında ise "Piknik" etkinliğini öner.
        //Sıcaklık 25'ten büyük ise "Yüzme" etkinliğini öner.
        if(heat<5){
            System.out.println("Kyak Yapabilirnizi.");
        } else if(heat>=5&&heat<15){
            System.out.println("Sinemaya Gidebiliriniz");
        } else if (heat>15&&heat<25) {
            System.out.println("Piknige gidebiliriniz");
        } else if (heat>25) {
            System.out.println("Yuzmeye gidebilirsiniz.");
        }
    }
}
