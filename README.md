```
using System;
```
```
namespace sinif_kavrami
{
    class Program
    {
        static void Main(string[] args)
        {
            //Söz Dizimi
            //class SinifAdi
            //{
            //    [Erişim Belirleyici] [Veri Tipi] OzellikAdi; 
            //    [Erişim Belirleyici] [Geri Donus Tipi] OzellikAdi; MetotAdi([Parametre Listesi])
            // {
            //  Metot Komutları   
            // }
            //}

            //Erişim Belirleyiciler
            // * Public (HERYERDEN ERİŞEBİLİR)
            // * Private (SADECE TANIMLADIĞI SINIF İÇERİSİNDE ERİŞİBİLİR)
            // * Internal (SADECE PROJE İÇERİSİNDE ERİŞEBİLİR)
            // * Protected (SADECE SINIF VE KALITIM SINIFLARDA ERİŞİLEBİLİR)

            Calisan calisan1 = new Calisan();
            calisan1.Ad = "Ayşe";
            calisan1.Soyad ="Kara";
            calisan1.No=23425634;
            calisan1.Departman="İnsan Kaynakları";

            calisan1.CalisanBilgileri();

            Console.WriteLine("************************" );

            Calisan calisan2 = new Calisan();

            calisan2.Ad = "Deniz";
            calisan2.Soyad ="Arda";
            calisan2.No=25646789;
            calisan2.Departman="Satın Alma";

            calisan2.CalisanBilgileri();

        }
    }
```
```
    class Calisan 
    {
        public string Ad;

        public string Soyad;

        public int No;

        public string Departman;
```
```

        public void CalisanBilgileri() 
        {
            Console.WriteLine("Çalışanın Adı:{0}", Ad);
            Console.WriteLine("Çalışanın Soyadı:{0}", Soyad);
            Console.WriteLine("Çalışanın No:{0}", No);
            Console.WriteLine("Çalışanın Departmanı:{0}", Soyad);
        }

    }
}
```

