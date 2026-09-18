---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonuna belirtilen dizinde ekler.  
Klonlanmış şekil, orijinalin konum ve boyutunu korur.

### Dönüş

Yeni oluşturulan [`IShape`](/slides/python-net/tr/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Klonlanmış şeklin ekleneceği sıfır tabanlı dizin. |
| source_shape | [`IShape`](/slides/python-net/tr/aspose.slides/ishape) | Klonlanacak [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonuna belirtilen dizinde ekler.  
Yeni şekil, `source_shape` öğesinin genişlik ve yüksekliğini korur.

### Dönüş

Yeni oluşturulan [`IShape`](/slides/python-net/tr/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Klonlanmış şeklin ekleneceği sıfır tabanlı dizin. |
| source_shape | [`IShape`](/slides/python-net/tr/aspose.slides/ishape) | Klonlanacak [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| x | **float** | Klonlanmış şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Klonlanmış şeklin çerçevesinin y koordinatı, puan cinsinden. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonuna belirtilen dizinde ekler.

### Dönüş

Yeni oluşturulan [`IShape`](/slides/python-net/tr/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Klonlanmış şeklin ekleneceği sıfır tabanlı dizin. |
| source_shape | [`IShape`](/slides/python-net/tr/aspose.slides/ishape) | Klonlanacak [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| x | **float** | Klonlanmış şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Klonlanmış şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Klonlanmış şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Klonlanmış şeklin çerçevesinin yüksekliği, puan cinsinden. |



### Bakınız
* sınıf [`IShape`](/slides/python-net/tr/aspose.slides/ishape)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)