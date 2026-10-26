---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Koleksiyona yeni bir hücre ekler.

```python
def add(self, chart_data_cell):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) | Eklenecek yeni hücre. |

## add(self, value) {#any}
[`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell)'yi belirtilen değerden oluşturur ve koleksiyona ekler.

```python
def add(self, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | **any** | Değer. |

### Açıklamalar

Bu yöntem AUTO_DATA adlı çalışma sayfasını ekler ve tüm değerleri oraya ekler.  [`IChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/ichartdataworkbook)'yi Hücre değerlerini eklemek veya düzenlemek için kullanırsanız, bu çalışma sayfasını kullanmadığınızdan emin olun
            Bu yöntemle eklenen değerlerin maksimum sayısı 16711680'i aşmamalıdır

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | limit aşıldığında |

### Bakınız
* sınıf [`IChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcellcollection)
* sınıf [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell)
* sınıf [`IChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/ichartdataworkbook)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)