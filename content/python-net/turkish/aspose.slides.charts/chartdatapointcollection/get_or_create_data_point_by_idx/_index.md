---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Koleksiyon zaten `index` dizinine sahip bir veri noktasını içeriyorsa bu veri noktasını döndürür.
            Koleksiyon `index`==N dizinine sahip bir veri noktası içermiyorsa (bu koleksiyondaki veri noktası sayısı N'den az veya eşit olduğunda) eksik veri noktalarını ekler ve sonuncusunu döndürür (isteği dizine sahip olan).
            Örneğin, koleksiyon indeksleri {0, 1, 2} ve istenen indeks 5'tir.
            Bu durumda yöntem eksik veri noktalarını ekler: {0, 1, 2, 3, 4, 5}. Ve indeks 5 olan veri noktasını döndürür.

### Dönüş

İstenen indeksli veri noktasını döndürür.

```python
def get_or_create_data_point_by_idx(self, index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | İndeks. |

### Ayrıca Bakınız
* sınıf [`ChartDataPointCollection`](/slides/python-net/tr/aspose.slides.charts/chartdatapointcollection)
* sınıf [`IChartDataPoint`](/slides/python-net/tr/aspose.slides.charts/ichartdatapoint)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)