---
title: add_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Bir sunuma resim ekler.

### Returns
Eklenen resim.

```python
def add_image(self, image):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/tr/aspose.slides/iimage) | Eklenmek istenen resim. |

### Remarks
Bu yöntem, WMF/EMF metafile'lerini sunuma eklemeden önce raster PNG görüntüsüne dönüştürür.

## add_image(self, stream) {#iorawiobase}
Bir akıştan sunuma resim ekler.

### Returns
Eklenen resim.

```python
def add_image(self, stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Resmin ekleneceği akış. |

### Remarks
Bu yöntem, WMF/EMF metafile'lerini raster PNG görüntüsüne dönüştürmeden sunuma ekleyebilir.

## add_image(self, buffer) {#bytes}
Belirtilen tampondan sunuma resim ekler.

### Returns
Eklenen resim.

```python
def add_image(self, buffer):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| buffer | **bytes** | Tampon. |

## add_image(self, image_source) {#ippimage}
Başka bir sunumdan bir resim kopyası ekler.

### Returns
Eklenen resim.

```python
def add_image(self, image_source):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage) | Kaynak resim. |

## add_image(self, svg_image) {#isvgimage}
SVG nesnesinden sunuma resim ekler.

### Returns
Eklenen resim.

```python
def add_image(self, svg_image):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage) | SVG resim nesnesi [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage) |

### Exceptions
| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | svgImage parametresi None olduğunda fırlatılır. |

## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Bir akıştan sunuma resim oluşturur ve ekler.

### Returns
Eklenen [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage).

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Resim dosyasının ekleneceği akış. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/tr/aspose.slides/loadingstreambehavior) | Akışa uygulanacak davranış. |

### Also See Also
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* sınıf [`IImageCollection`](/slides/python-net/tr/aspose.slides/iimagecollection)
* sınıf [`IPPImage`](/slides/python-net/tr/aspose.slides/ippimage)
* sınıf [`ISvgImage`](/slides/python-net/tr/aspose.slides/isvgimage)
* enum [`LoadingStreamBehavior`](/slides/python-net/tr/aspose.slides/loadingstreambehavior)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)