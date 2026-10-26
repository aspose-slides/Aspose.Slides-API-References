---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.charts/chartseriescollection/add/
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
Yeni bir grafik serisini [`ChartDataCell`](/slides/python-net/tr/aspose.slides.charts/chartdatacell) üzerinden oluşturur ve koleksiyona ekler.

### Döndürür

Eklenen grafik serisi ya da zaten koleksiyonda olan seri.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell) | Seri adını içeren hücre. |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Seri tipini ayarlar. |

### Açıklamalar

Eğer aynı hücreden oluşturulan grafik serisi zaten koleksiyonda ise, yöntem hiçbir şey eklemez ve dizinini döndürür.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Yeni bir grafik serisini [`ChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/chartcellcollection) üzerinden oluşturur ve koleksiyona ekler.

### Döndürür

Eklenen grafik serisi ya da zaten koleksiyonda olan seri.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcellcollection) | Seri adını içeren hücreler. |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Seri tipini ayarlar. |

### Açıklamalar

Eğer aynı hücreden oluşturulan grafik serisi zaten koleksiyonda ise, yöntem hiçbir şey eklemez ve dizinini döndürür.


## add(self, name, type) {#str-charttype}
Yeni bir grafik serisini değer üzerinden oluşturur ve koleksiyona ekler.

### Döndürür

Eklenen grafik serisi.



```python
def add(self, name, type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | **str** | Seri adı. |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Seri tipini ayarlar. |



### Ayrıca Bakınız
* sınıf [`ChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/chartcellcollection)
* sınıf [`ChartDataCell`](/slides/python-net/tr/aspose.slides.charts/chartdatacell)
* sınıf [`ChartSeriesCollection`](/slides/python-net/tr/aspose.slides.charts/chartseriescollection)
* enum [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype)
* sınıf [`IChartCellCollection`](/slides/python-net/tr/aspose.slides.charts/ichartcellcollection)
* sınıf [`IChartDataCell`](/slides/python-net/tr/aspose.slides.charts/ichartdatacell)
* sınıf [`IChartSeries`](/slides/python-net/tr/aspose.slides.charts/ichartseries)
* modül [`aspose.slides.charts`](/slides/python-net/tr/aspose.slides.charts)
* kütüphane [`Aspose.Slides`](/slides/python-net)