---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Oluşturulacak grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni grafiğin genişliği, nokta cinsinden. |
| height | **float** | Yeni grafiğin yüksekliği, nokta cinsinden. |
| index | **int** | Şekil koleksiyonunda yeni grafiğin ekleneceği sıfır tabanlı dizin. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parametre | Tip | Açıklama |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype) | Oluşturulacak grafiğin türü. |
| x | **float** | Yeni grafiğin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni grafiğin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni grafiğin genişliği, nokta cinsinden. |
| height | **float** | Yeni grafiğin yüksekliği, nokta cinsinden. |
| index | **int** | Şekil koleksiyonunda yeni grafiğin ekleneceği sıfır tabanlı dizin. |
| init_with_sample | **bool** | Yeni grafiği örnek seri verileri ve ayarlarla başlatmak için true;<br/><br/>            seri olmadan ve yalnızca minimum ayarlarla grafiği oluşturmak için false, bu da oluşturmayı hızlandırır. |



### Ayrıca Bakınız
* enum [`ChartType`](/slides/python-net/tr/aspose.slides.charts/charttype)
* sınıf [`IChart`](/slides/python-net/tr/aspose.slides.charts/ichart)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)