---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Koleksiyona yeni cell ekler.

```python
def add(self, cell):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) | Eklenmek üzere yeni cell. |

## add(self, value) {#any}
[`ChartDataCell`](/slides/python-net/tr/aspose.slides.charts/chartdatacell)'yi belirtilen değerden oluşturur ve koleksiyona ekler.

```python
def add(self, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | **any** | Değer. |

### Açıklamalar
Bu yöntem AUTO_DATA adlı çalışma sayfasını ekler ve tüm değerleri oraya ekler.  Eğer [`ChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/chartdataworkbook) ile Cell değerlerini eklemek veya düzenlemek isterseniz, bu çalışma sayfasını kullanmadığınızdan emin olun
            Bu yöntemle eklenen değerlerin maksimum sayısı 16711680'i aşmamalıdır

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | limit aşılırsa |

### Bakınız
* sınıf [`ChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/chartcellcollection)
* sınıf [`ChartDataCell`](/slides/python-net/tr/aspose.slides.charts/chartdatacell)
* sınıf [`ChartDataWorkbook`](/slides/python-net/tr/aspose.slides.charts/chartdataworkbook)
* sınıf [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)