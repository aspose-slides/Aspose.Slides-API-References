---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
WebVTT kapalı altyazıları koleksiyonun sonuna ekler.

### Döndürür

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
| **RuntimeError(Proxy error(ArgumentNullException))** | `file_path` `None` ise fırlatılır. |
| **RuntimeError(Proxy error(ArgumentException))** | `file_path` boş ise fırlatılır. |


## add(self, label, stream) {#str-iorawiobase}
WebVTT kapalı altyazıları bir akıştan koleksiyonun sonuna ekler.

### Döndürür

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
| **RuntimeError(Proxy error(ArgumentNullException))** | `stream` `None` ise fırlatılır. |
| **RuntimeError(Proxy error(ArgumentException))** | Giriş verisi WebVTT formatında değilse fırlatılır. |



### Bkz.
* sınıf [`CaptionsCollection`](/slides/python-net/tr/aspose.slides/captionscollection)
* sınıf [`ICaptions`](/slides/python-net/tr/aspose.slides/icaptions)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)