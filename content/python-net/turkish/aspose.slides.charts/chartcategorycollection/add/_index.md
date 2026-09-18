---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Eğer kategori koleksiyonda mevcutsa, onu döndürür. Aksi takdirde [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) öğesinden yeni bir grafik kategorisi oluşturur ve koleksiyona ekler.

### Returns
Eklenmiş veya mevcut kategori.

```python
def add(self, chart_data_cell):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) | Grafik kategorisi oluşturmak için kullanılan hücre. |

## add(self, value) {#any}
Değerden yeni bir [`ChartCategory`](/slides/python-net/tr/aspose.slides.charts/chartcategory) oluşturur ve koleksiyona ekler.

### Returns
Eklenen [`IChartCategory`](/slides/python-net/tr/aspose.slides.charts/ichartcategory).

```python
def add(self, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | **any** | Değer. |

### Remarks
Bu yöntem, AUTO_DATA adlı bir çalışma sayfası ekler ve tüm değerleri oraya ekler. Eğer [`ChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/chartdataworkbook) kullanarak hücre değerlerini ekleyip düzenliyorsanız, bu çalışma sayfasını kullanmadığınızdan emin olun. Bu yöntemle eklenen değerlerin maksimum sayısı 16711680'i aşmamalıdır.

### Exceptions
| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | limit aşılırsa |

### See Also
* sınıf [`ChartCategory`](/slides/python-net/tr/aspose.slides.charts/chartcategory)
* sınıf [`ChartCategoryCollection`](/slides/python-net/tr/aspose.slides.charts/chartcategorycollection)
* sınıf [`ChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/chartdataworkbook)
* sınıf [`IChartCategory`](/slides/python-net/tr/aspose.slides.charts/ichartcategory)
* sınıf [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)