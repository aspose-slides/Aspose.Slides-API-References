---
title: add_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Başka bir sunumdan bir görüntünün kopyasını ekler.

### Dönüş

Eklenen görüntü.

```python
def add_image(self, image_source):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | Kaynak görüntü. |

## add_image(self, image) {#iimage}
Bir sunuma bir görüntü ekler.

### Dönüş

Eklenen görüntü.

```python
def add_image(self, image):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/tr/aspose.slides/iimage) | Eklenecek görüntü. |

### Açıklama

Bu yöntem, WMF/EMF metafilelerini bir sunuma eklemeden önce raster PNG görüntüsüne dönüştürür.

## add_image(self, stream) {#iorawiobase}
Bir akıştan bir sunuma bir görüntü ekler.

### Dönüş

Eklenen görüntü.

```python
def add_image(self, stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Görüntünün ekleneceği akış. |

### Açıklama

Bu yöntem, WMF/EMF metafilelerini raster PNG görüntüsüne dönüştürmeden bir sunuma ekleyebilir.

## add_image(self, buffer) {#bytes}
Belirtilen tampondan bir sunuma bir görüntü ekler.

### Dönüş

Eklenen görüntü.

```python
def add_image(self, buffer):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| buffer | **bytes** | Tampon. |

## add_image(self, svg_image) {#isvgimage}
Bir Svg nesnesinden bir sunuma bir görüntü ekler.

### Dönüş

Eklenen görüntü.

```python
def add_image(self, svg_image):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage) | Svg görüntü nesnesi [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage) |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | svgImage parametresi None olduğunda. |

## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Bir akıştan bir görüntü oluşturur ve bir sunuma ekler.

### Dönüş

Eklenen [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage).

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Görüntünün ekleneceği akış. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/tr/aspose.slides/loadingstreambehavior) | Akışa uygulanacak davranış. |

### İlgili
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* sınıf [`ImageCollection`](/slides/python-net/tr/aspose.slides/imagecollection)
* sınıf [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* sınıf [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage)
* enum [`LoadingStreamBehavior`](/slides/python-net/tr/aspose.slides/loadingstreambehavior)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)