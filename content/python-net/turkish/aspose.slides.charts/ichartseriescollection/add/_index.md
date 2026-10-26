---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Yeni bir grafik serisi oluşturur ve koleksiyona ekler.

### Döndürür

Yeni grafik serisi.



```python
def add(self, type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Serinin türü |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Yeni bir grafik serisi [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) kaynağından oluşturur ve koleksiyona ekler.

### Döndürür

Eklenen grafik serisi ya da zaten koleksiyonda bulunan seri.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) | Seri adını içeren hücre. |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | type serinin türünü ayarlar |

### Açıklamalar

Eğer aynı hücreden oluşturulan grafik serisi zaten koleksiyonda varsa, metod hiçbir şey eklemez ve indeksini döndürür.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Yeni bir grafik serisi [`IChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcellcollection) kaynağından oluşturur ve koleksiyona ekler.

### Döndürür

Eklenen grafik serisi ya da zaten koleksiyonda bulunan seri.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcellcollection) | Seri adını içeren hücreler. |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | type serinin türünü ayarlar |

### Açıklamalar

Eğer aynı hücreden oluşturulan grafik serisi zaten koleksiyonda varsa, metod hiçbir şey eklemez ve indeksini döndürür.


## add(self, name, type) {#str-charttype}
Yeni bir grafik serisi değerden oluşturur ve koleksiyona ekler.

### Döndürür

Eklenen grafik serisi.



```python
def add(self, name, type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | **str** | Seri adı. |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | type serinin türünü ayarlar |



### İlgili
* enumeration [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype)
* class [`IChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcellcollection)
* class [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell)
* class [`IChartSeries`](/slides/python-net/tr/aspose.slides.charts/ichartseries)
* class [`IChartSeriesCollection`](/slides/python-net/tr/aspose.slides.charts/ichartseriescollection)
* module [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)