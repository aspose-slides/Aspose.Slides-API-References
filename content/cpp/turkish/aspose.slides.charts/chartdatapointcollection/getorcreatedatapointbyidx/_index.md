---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ API Referansı
description: "Eğer koleksiyon zaten index index indeksine sahip bir veri noktası içeriyorsa bu veri noktasını döndürür. Eğer koleksiyon index index ==N (bu koleksiyondaki veri noktası sayısı N'den az veya N'ye eşit olduğunda) indeksine sahip bir veri noktası içermiyorsa eksik veri noktalarını ekler ve istenen indekse sahip son veri noktasını döndürür. Örneğin, koleksiyon indeksleri {0, 1, 2} ve istenen indeks 5'tir. Bu durumda yöntem eksik veri noktalarını ekler: {0, 1, 2, 3, 4, 5}. Ve indeks 5'e sahip veri noktasını döndürür."
type: docs
weight: 170
url: /tr/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) yöntemi


If collection already contains data point with index *index* then returns this data point. If collection doesn't contains data point with index *index* ==N (when number of data points in this collection is less or equal then N) then adds deficient data points and returns last (which has requested index). For example, collection indexes are {0, 1, 2}, and requested index is 5. Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **uint32_t** | İndeks. |

### Dönüş Değeri

İstenen indeks ile veri noktasını döndürür.

## Diğerlerine Bak

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartDataPoint](../../ichartdatapoint/)
* Sınıf [ChartDataPointCollection](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)