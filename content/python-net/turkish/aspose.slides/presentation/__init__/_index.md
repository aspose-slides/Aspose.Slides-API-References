---
title: Presentation constructor
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Bu yapıcı yeni bir sunumu sıfırdan oluşturur.
            Oluşturulan sunumda bir boş slayt bulunur.

```python
def __init__(self):
    ...
```

## __init__(self, load_options) {#loadoptions}
Bu yapıcı yeni bir sunumu sıfırdan oluşturur.
            Oluşturulan sunumda bir boş slayt bulunur.

```python
def __init__(self, load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/tr/aspose.slides/loadoptions) | Ek yükleme seçenekleri. |

## __init__(self, stream) {#iorawiobase}
Bu yapıcı mevcut bir Sunumu okumanın birincil mekanizmasıdır.

```python
def __init__(self, stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Giriş akışı. |

## __init__(self, file) {#str}
Bu yapıcı, Sunumun içeriğinin okunduğu kaynak dosya yolunu alır.

```python
def __init__(self, file):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file | **str** | Giriş dosyası. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Giriş dosyası sıfır uzunluğa sahip olduğunda fırlatılır |

## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Bu yapıcı mevcut bir Sunumu okumanın birincil mekanizmasıdır.

```python
def __init__(self, stream, load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Giriş akışı. |
| load_options | [`LoadOptions`](/slides/python-net/tr/aspose.slides/loadoptions) | Ek yükleme seçenekleri. |

## __init__(self, file, load_options) {#str-loadoptions}
Bu yapıcı, Sunumun içeriğinin okunduğu kaynak dosya yolunu alır.

```python
def __init__(self, file, load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file | **str** | Giriş dosyası. |
| load_options | [`LoadOptions`](/slides/python-net/tr/aspose.slides/loadoptions) | Ek yükleme seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Giriş dosyası sıfır uzunluğa sahip olduğunda fırlatılır |

### Ayrıca Bakınız
* sınıf [`LoadOptions`](/slides/python-net/tr/aspose.slides/loadoptions)
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)