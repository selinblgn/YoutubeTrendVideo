# YouTube Trending Video Dataset Üzerinde Denetimli ve Denetimsiz Öğrenme

Bu proje, Kaggle'dan alınan **YouTube Trending Video Dataset** üzerinde hem denetimli hem de denetimsiz öğrenme tekniklerini kullanarak bir analiz yapmaktadır. 

## Kullanılan Modeller:
1. **Denetimli Öğrenme:** Lojistik Regresyon
    - Hedef: Viral (1 milyon izlenmeyi aşan) videoları tahmin etmek.
    - Performans metrikleri: F1 Skoru.
    
2. **Denetimsiz Öğrenme:** K-Means Kümeleme
    - Hedef: Videoları izlenme, beğeni ve etkileşimlere göre kümelere ayırmak.

## Veri Seti:
Kullanılan veri seti [Kaggle YouTube Trending Video Dataset](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset) olup 10MB'den büyük bir veri setidir. 

YouTube Trending Video Dataset'in meta verileri şunları içerir:


Video Kimliği: Her video için benzersiz bir tanımlayıcı

Trend Tarihi: Videonun trend olduğu tarih

Başlık: Videonun adı

Kanal Adı: Videoyu yayınlayan kanal

Kategori Kimliği: Video kategorisini gösteren sayısal kimlik

Yayınlanma Zamanı: Videonun yayınlanma tarihi

Görüntüleme, Beğenme, Beğenmeme, Yorum Sayısı: İzleyici etkileşim metrikleri

Etiketler: Video ile ilgili anahtar kelimeler



## Gereksinimler:
- Python 3.7+
- Pandas
- Scikit-learn
- Matplotlib



## Sonuçlar:
- Lojistik Regresyon modeli viral videoları %99'in üzerinde F1 skoru ile başarıyla tahmin etti.
- K-Means kümeleme algoritması, videoları 3 ana kümeye ayırarak etkileşim bazlı segmentasyon yaptı.

## Adresler:
-Kaggle Notebook:https://www.kaggle.com/code/ayeselinbilgin/youtube-trend-data-analysis
-Kaggle Dataset:https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset
