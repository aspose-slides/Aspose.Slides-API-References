---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
WebVTT kapalı altyazıları koleksiyonun sonuna ekler.

### Dönüş

Eklenen [`ICaptions`](/slides/python-net/tr/aspose.slides/icaptions) örneği.



```python
def add(self, label, file_path):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| label | **str** | Kapalı altyazıların etiketi. |
| file_path | **str** | WebVTT dosyasının yolu. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Eğer `file_path` `None` ise atılır. |
| **RuntimeError(Proxy error(ArgumentException))** | Eğer `file_path` boş ise atılır. |


## add(self, label, stream) {#str-iorawiobase}
WebVTT kapalı altyazıları bir akıştan koleksiyonun sonuna ekler.

### Dönüş

Eklenen [`ICaptions`](/slides/python-net/tr/aspose.slides/icaptions) örneği.



```python
def add(self, label, stream):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| label | **str** | Kapalı altyazıların etiketi. |
| stream | **io.RawIOBase** | WebVTT formatında veri içeren giriş akışı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Eğer `stream` `None` ise atılır. |
| **RuntimeError(Proxy error(ArgumentException))** | Eğer giriş verisi WebVTT formatında değilse atılır. |



### Bakınız
* sınıf [`ICaptions`](/slides/python-net/tr/aspose.slides/icaptions)
* sınıf [`ICaptionsCollection`](/slides/python-net/tr/aspose.slides/icaptionscollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)