# Gezinomi-Data-Analysis-Project

Bu proje Miuul Data Analyst Bootcamp dahilinde olan Final Projesi için hazırlanmıştır.

           --- Yol Haritası ---
İlk aşamada verinin SQL serverdan csv olarak importlanması.
Verinin genel bir tabloda gözlenmesi ve sorunların tespit edilmesi.
Türkçe karakter sorunu tespit edildi.
Türkçe karakterler için bir fonksiyon tanımlanması.
Replace metodu ile Türkçe karakterlerin düzeltilmesi.
Duplicate verilerin tespit edilmesi.
Duplicate kolonların veriden droplanması.
N/A verilerin tespit edilmesi.
N/A verilerin kendi alanlarında gruplanmış benzer ortalamaları ile doldurulması.
Veri seti içinde Unique olan şehirlerin tespiti ve bu şehirlerin frekanslarının hesaplanması.
Şehir bazında toplam satış miktarlarına ve Price değişkenine göre kazanılan miktarların hesaplanması.
Konseptlere göre satışların belirlenmesi ve toplam kazançların hesaplanması.
Şehirlerin ortalama Price'ının hesaplanması.
Booking Type olarak bir değişken oluşturulması.
SaleDate ve CheckInDate arasındaki zaman farkında göre sınıflandırma yapılması.
Bu sınıflandırılan satışların BookingType içine kayıt edilmesi.
Verinin farklı değişkenlere göre görselleştirilmesi.
Farklı değişkenlerle oluşturulmuş DataFrame'lerin yeni csv'ler olarak kayıt edilmesi.
Her şehir için ayrı ayrı csv dosyalarının kayıt edilmesi.
(Bu aşamada farklı csv'leri çıktı alarak kayıt etme nedenimiz görselleştirme aşamasında ve farklı BI toollarında
dosyaları işlerken daha düşük işlem gücüyle görselleştirmenin yükünün hafifletilemsi.)
Potansiyel bir Machine Learning kullanımı için veri setini LazyClassifier ve LazyRegressor ile test edilmesi.
Power Bı ile görselleştirmeye geçiş.
