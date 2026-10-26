---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.
Klonlanan şekil, orijinalin konum ve boyutunu korur.

### Dönüş
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
Yeni şekil, `source_shape`ın genişlik ve yüksekliğini korur.

### Dönüş
Yeni oluşturulan [`IShape`](/slides/python-net/tr/aspose.slides/ishape).

```python
def add_clone(self, source_shape, x, y):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/tr/aspose.slides/ishape) | Klonlanacak [`IShape`](/slides/python-net/tr/aspose.slides/ishape). |
| x | **float** | Klonlanan şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Klonlanan şeklin çerçevesinin y koordinatı, puan cinsinden. |

## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.

### Dönüş
Yeni oluşturulan [`IShape`](/slides/python-net/tr/aspose.slides/ishape).

```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/tr/aspose.slides/ishape) | Klonlanacak şekil. |
| x | **float** | Klonlanan şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Klonlanan şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Klonlanan şeklin çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Klonlanan şeklin çerçevesinin yüksekliği, puan cinsinden. |

### Ayrıca Bakınız
* sınıf [`IShape`](/slides/python-net/tr/aspose.slides/ishape)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)