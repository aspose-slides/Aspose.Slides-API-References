---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarla başlatır ve onu belirtilen dizindeki şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart).

```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Oluşturulacak grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | **float** | Yeni grafiğin genişliği, puan cinsinden. |
| height | **float** | Yeni grafiğin yüksekliği, puan cinsinden. |
| index | **int** | Şekil koleksiyonuna yeni grafiğin ekleneceği sıfır tabanlı dizin. |

## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarla başlatır ve onu belirtilen dizindeki şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart).

```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Oluşturulacak grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | **float** | Yeni grafiğin genişliği, puan cinsinden. |
| height | **float** | Yeni grafiğin yüksekliği, puan cinsinden. |
| index | **int** | Şekil koleksiyonuna yeni grafiğin ekleneceği sıfır tabanlı dizin. |
| init_with_sample | **bool** | Yeni grafiği örnek seri verileri ve ayarlarla başlatmak için true; <br/><br/>            grafiği seri olmadan ve yalnızca minimum ayarlarla oluşturmak için false, bu da oluşturmayı daha hızlı yapar. |

### Diğer
* enum [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype)
* sınıf [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)