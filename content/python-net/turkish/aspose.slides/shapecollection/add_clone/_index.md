---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.
Klonlanan şekil, orijinalin konum ve boyutunu korur.

### Returns

Yeni oluşturulan [`IShape`](/slides/python-net/tr/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/tr/aspose.slides/ishape) | Klonlanacak [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.
Yeni şekil, `source_shape`'ın genişlik ve yüksekliğini korur.

### Returns

Yeni oluşturulan [`IShape`](/slides/python-net/tr/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/tr/aspose.slides/ishape) | Klonlanacak şekil. |
| x | **float** | Yeni şeklin çerçevesinin x-koordinatı, nokta cinsinden. |
| y | **float** | Yeni şeklin çerçevesinin y-koordinatı, nokta cinsinden. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.

### Returns

Yeni oluşturulan [`IShape`](/slides/python-net/tr/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/tr/aspose.slides/ishape) | Klonlanacak şekil. |
| x | **float** | Yeni şeklin çerçevesinin x-koordinatı, nokta cinsinden. |
| y | **float** | Yeni şeklin çerçevesinin y-koordinatı, nokta cinsinden. |
| width | **float** | Yeni şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni şeklin çerçevesinin yüksekliği, nokta cinsinden. |



### See Also
* sınıf [`IShape`](/slides/python-net/tr/aspose.slides/ishape)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)