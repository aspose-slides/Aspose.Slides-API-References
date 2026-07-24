---
title: GetOrCreateDataPointByIdx()
second_title: C++ için Aspose.Slides API Referansı
description: "Eğer koleksiyon zaten index indeksinde bir veri noktasına sahipse, bu veri noktasını döndürür. Eğer koleksiyon index ==N indeksinde bir veri noktasına sahip değilse (bu koleksiyondaki veri noktası sayısı N'den az veya N'ye eşit olduğunda), eksik veri noktalarını ekler ve istenen indekse sahip olan sonuncusunu döndürür. Örneğin, koleksiyon indeksleri {0, 1, 2} ve istenen indeks 5'tir. Bu durumda metod eksik veri noktalarını ekler: {0, 1, 2, 3, 4, 5}. Ve indeks 5'teki veri noktasını döndürür."
type: docs
weight: 131
url: /tr/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metodu


Eğer koleksiyon zaten *index* dizininde bir veri noktasına sahipse, bu veri noktasını döndürür. Eğer koleksiyon *index* ==N dizininde bir veri noktasına sahip değilse (bu koleksiyondaki veri noktalarının sayısı N'den az veya N'ye eşit olduğunda), eksik veri noktalarını ekler ve isteğe bağlı dizine sahip olan sonuncusunu döndürür. Örneğin, koleksiyon dizinleri {0, 1, 2} ve istenen dizin 5'tir. Bu durumda metod eksik veri noktalarını ekler: {0, 1, 2, 3, 4, 5}. Ve dizin 5'teki veri noktasını döndürür.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **uint32_t** | İndeks. |

### Dönüş Değeri

İstenen dizine sahip veri noktasını döndürür.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartDataPoint](../../ichartdatapoint/)
* Sınıf [IChartDataPointCollection](../)
* Ad Alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)