import java.util.Calendar;

public class Stunden {

	public static void main(String [] args) {
		
		Calendar cal = Calendar.getInstance ();
	
               
		 int Stunden =  cal.get( Calendar.HOUR_OF_DAY );
		 int Minuten =  cal.get(Calendar.MINUTE);
		 int Sekunden =  cal.get(Calendar.SECOND);
	
		int MinutenamTag = Stunden * 60;
		int MinutenamTagganz = MinutenamTag + Minuten;
		int SekundenamTag = MinutenamTagganz * 60;
		int SekundenamTagganz = SekundenamTag + Sekunden;
		 
		System.out.println("Seit Mitternacht sind " + SekundenamTagganz + " Sekunden vergangen.");
		 
		
		 int bisMitternachtStunden = 24- Stunden;
		 int bisMitternachtStundenganz = bisMitternachtStunden * 60;
		 int bisMitternachtMinuten = bisMitternachtStundenganz + Minuten;
		 int bisMitternachtSekunden = bisMitternachtMinuten * 60;
		 int bisMitternachtSekundenganz = bisMitternachtSekunden + Sekunden;
		
		 System.out.println("Bis Mitternacht " + " vergehen noch " + bisMitternachtSekundenganz + " Sekunden.");
		 
		 //System.out.println(bisMitternachtStunden);
		 //System.out.println(bisMitternachtMinuten);
		 //System.out.println(bisMitternachtSekunden);
		 
		 int ganzerTagSekunden =  86400;
		 double zwischenschritt1 = SekundenamTagganz * 100.00;
		 double vergangeProtzente = zwischenschritt1 / ganzerTagSekunden;
		 
		 System.out.println("Es sind seit Mitternacht schon " + vergangeProtzente + " Prozent des Tages vergangen.");
		 
	
	}
}
