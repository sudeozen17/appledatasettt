Veri Seti Hakkında
Bu proje için kullanılan veri seti, Apple Inc.'in hisse senedi kapanış fiyatlarını içerir. Veri seti, 2020 - 2024 yılları arasında Apple hisse senedi fiyatlarının günlük kapanış değerlerini kapsamaktadır.
Veri Kümesi Yapısı
Veri seti, aşağıdaki sütunları içeren bir CSV dosyasıdır:
Tarih (Tarih): Hisse senedine ait veri kaydının alındığı tarih. (YYYY-AA-GG formatında)
Open (Açılış Fiyatı): Hisse senedinin gün başlangıcındaki fiyatı (USD).
Yüksek (En Yüksek Fiyat): Gündeki en yüksek hisse senedi fiyatı (USD).
Düşük (En Düşük Fiyat): Günün içindeki en düşük hisse senedi fiyatı (USD).
Close (Kapanış Fiyatı): Hisse senedinin gün sonunda kapanış fiyatı (USD).
Volume (İşlem Hacmi): Gün boyunca işlem gören toplam hisse adedi.
Veri Setinin Kaynağı
Bu veri seti, halka açık finansal veri kaynaklarından derlenmiştir ve Apple Inc.'in hisse senedi kapanış fiyatlarına odaklanmaktadır. Veri seti, zaman serisi analizleri ve finansal tahmin modelleri üzerinde çalışmalar yapmak uygundur.
Kullanım Alanları
Bu veri seti, özellikle zaman serisi tahmini ve finansal analiz çalışmaları için uygundur. Projede kullanılan LSTM (Long Short-Term Memory) modelinde, veri setinin son 60 gün kullanılarak bir sonraki günün fiyat tahmini yapılmıştır.
Örnek Satırlar
Tarih Açılış Yüksek Düşük Kapanış Hacim
2020-01-02 296,24 299,50 293,65 297,43 33870100
2020-01-03 297,15 300,58 296,50 297,84 32159800
06.01.2020 293.79 299.96 292.75 299.80 30382200


https://www.kaggle.com/code/sudezen1734/notebooke833415b1c
https://www.kaggle.com/datasets/sudezen1734/appledataset/data
