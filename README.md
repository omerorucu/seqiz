# SeQiz

**Sınav değerlendirme ve öğrenme çıktısı analizi**

SeQiz, üniversitelerde yapılan test ve yazılı sınavları değerlendiren, sonuçları dersin öğrenme çıktıları ve programın program çıktılarıyla ilişkilendiren bir Windows masaüstü programıdır.

## Neler yapar

- Taranmış optik cevap formlarını (JPG) okur; öğrenci numarası, kitapçık türü ve cevaplar formdaki kodlamadan alınır.
- Cevap anahtarı Excel'den, taranmış bir formdan ya da program içindeki tablodan girilir; kitapçık türleri ayrı ayrı tanımlanır.
- Puanlama ayarlanabilir (soru puanları, yanlışın doğruyu götürmesi, iptal edilen sorular).
- Sınav istatistikleri: puan dağılımı, soru bazında doğru / yanlış / boş sayıları, soru analizi.
- Öğrenme çıktısı analizi: her soru bir öğrenme çıktısıyla eşlenir; çıktı bazında başarı, hedefe ulaşma durumu ve program çıktılarına katkı hesaplanır.
- Yazılı (açık uçlu) sınavlar: soru bazında notlar girilir ya da Excel'den yapıştırılır; aynı analizler üretilir.
- Alt dersler: ders kurulu (komite), modül ve proje derslerinde alt ders bazında başarı ve isteğe bağlı baraj uygulaması.
- Çıktılar: PDF rapor, öğrenci karnesi ve Excel dosyası.

## Kurulum

1. [Sürümler](../../releases/latest) sayfasından `SeQiz.exe` dosyasını indirin. Kurulum gerekmez; dosya çift tıklanarak çalışır.
2. Hazır ders dosyalarını kullanmak isterseniz `SeQiz_dersler.zip` dosyasını da indirin ve `SeQiz.exe` ile aynı klasöre açın. Zip içinden çıkan `dersler` klasörü exe'nin yanında durmalıdır.

`SeQiz.exe` dijital olarak imzalıdır (yayımcı: Omer Kamil Orucu). Windows 10 ve 11'de çalışır.

## Hazır ders dosyaları

`SeQiz_dersler.zip`, üniversitelerin herkese açık Bologna bilgi paketlerinden alınan ders dosyalarını içerir. Her ders bir Excel dosyasıdır; içinde dersin öğrenme çıktıları, programın program çıktıları ve öğrenme çıktısı – program çıktısı katkı düzeyleri bulunur.

- **Süleyman Demirel Üniversitesi:** 18 lisans birimi (fakülteler, Sivil Havacılık Yüksekokulu, Enformatik)
- **Bursa Teknik Üniversitesi:** Orman Fakültesi (Orman Mühendisliği, Orman Endüstri Mühendisliği)

Toplam yaklaşık 11.700 ders. Bilgi paketinde öğrenme çıktısı girilmemiş derslerin dosyasında çıktı listesi boştur; ayrıntılar her fakülte klasöründeki `KAYNAK.txt` dosyasında yazılıdır. Ders dosyaları programdan düzenlenebilir; kendi dersinizi sıfırdan da tanımlayabilirsiniz.

## Geliştirici

Ömer K. Örücü

Bu depo dağıtım deposudur; kaynak kod içermez.

---

**SeQiz** is a Windows desktop application for grading multiple-choice and written exams and for linking the results to course learning outcomes and programme outcomes. It reads scanned optical answer sheets, scores them, and produces item statistics, learning-outcome attainment reports, student report cards and Excel output. The interface is in Turkish.
