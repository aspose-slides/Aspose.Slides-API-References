---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Yeni bir grafik oluşturur, örnek seriler verisi ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Eklenecek grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | **float** | Grafiğin genişliği, puan cinsinden. |
| height | **float** | Grafiğin yüksekliği, puan cinsinden. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Yeni bir grafik oluşturur, örnek seriler verisi ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Eklenecek grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | **float** | Grafiğin genişliği, puan cinsinden. |
| height | **float** | Grafiğin yüksekliği, puan cinsinden. |
| init_with_sample | **bool** | True, yeni grafiği örnek seri verileri ve ayarlarla başlatmak için; <br/><br/>false, grafiği seri olmadan ve yalnızca minimum ayarlarla oluşturmak için, bu da oluşturmayı<br/><br/>daha hızlı yapar. |



### Ayrıca Bakınız
* enum [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype)
* sınıf [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)