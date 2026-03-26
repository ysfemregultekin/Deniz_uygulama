# 🦷 İmplant Fiyat Hesaplayıcı Pro

Bu proje, diş hekimleri, klinikler ve implant satıcıları için özel olarak geliştirilmiş; detaylı maliyet analizi ve kâr marjı hesaplaması yapan pratik bir web uygulamasıdır. 

## 🌟 Özellikler

- **Akıllı Maliyet Hesaplama:** İmplant, abutment ve multiunit adetlerine göre toplam maliyeti saniyeler içinde çıkarır.
- **Otomatik Cerrahi Set Hesabı:** Girilen her 100 implant için sisteme otomatik olarak 1 adet cerrahi set maliyeti yansıtılır (1-100 arası 1 set, 101-200 arası 2 set vb.).
- **Bedelsiz Abutment Mantığı:** Girilen abutment adetinin %20'si bedelsiz (hediye) olarak kabul edilir ve maliyet kalan %80 üzerinden hesaplanır.
- **Kâr Marjı ve Satış Fiyatı:** Hedeflenen brüt kâr marjı (%) girildiğinde, elde edilmesi gereken satış fiyatını hesaplar ve doğruluğunu ispatlayan matematiksel sağlamasını sunar.
- **Gelişmiş Ayarlar Menüsü:** - Farklı implant markaları ve birim fiyatları eklenebilir, silinebilir ve sekmeler arası kolayca geçiş yapılabilir.
  - Abutment, multiunit ve cerrahi set gibi sabit maliyet kalemlerinin fiyatları tek bir ekrandan güncellenebilir.
- **Veri Kaydı:** Girilen tüm marka ve fiyat ayarları tarayıcı hafızasında (LocalStorage) tutulur, sayfayı kapatsanız bile verileriniz silinmez.

## 🚀 Nasıl Kullanılır?

1. Uygulamayı açtığınızda öncelikle **⚙️ Ayarlar** sekmesine gidin.
2. Sabit maliyet kalemlerini (abutment, multiunit, cerrahi set) güncelleyip kaydedin.
3. Çalıştığınız implant markalarını ve birim fiyatlarını listeye ekleyin.
4. Üst kısımdan işlem yapmak istediğiniz **Marka sekmesine** tıklayın.
5. Adetleri ve hedeflediğiniz kâr marjını girip **Hesapla** butonuna basın. Alt kısımda detaylı maliyet dökümünü göreceksiniz.

## 🛠️ Teknolojiler

Bu uygulama herhangi bir sunucu veya veritabanı kurulumuna ihtiyaç duymadan, tamamen mobil uyumlu statik web teknolojileri kullanılarak geliştirilmiştir:
- HTML5
- CSS3
- Vanilla JavaScript
