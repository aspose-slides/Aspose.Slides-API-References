---
title: save method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Görüntüyü bir dosyaya kaydeder.


```python
def save(self, filename):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| filename | **str** | Görüntünün kaydedileceği dosyanın yolu. |


## save(self, filename, format) {#str-imageformat}
Görüntüyü belirtilen biçimde bir dosyaya kaydeder.


```python
def save(self, filename, format):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| filename | **str** | Görüntünün kaydedileceği dosyanın yolu. |
| format | [`ImageFormat`](/slides/python-net/tr/aspose.slides/imageformat) | Görüntü biçimi. |


## save(self, stream, format) {#iorawiobase-imageformat}
Görüntüyü belirtilen biçimde bir akışa kaydeder.


```python
def save(self, stream, format):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Görüntünün kaydedileceği akış. |
| format | [`ImageFormat`](/slides/python-net/tr/aspose.slides/imageformat) | Görüntü biçimi. |


## save(self, filename, format, quality) {#str-imageformat-int}
Görüntüyü belirtilen biçimde ve kalitede bir dosyaya kaydeder.


```python
def save(self, filename, format, quality):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| filename | **str** | Görüntünün kaydedileceği dosyanın yolu. |
| format | [`ImageFormat`](/slides/python-net/tr/aspose.slides/imageformat) | Görüntü biçimi. |
| quality | **int** | Kaydedilen görüntünün kalitesi (0 ile 100 arasında).  <br/><br/>            Bu parametre yalnızca [`ImageFormat.JPEG`](/slides/python-net/tr/aspose.slides/imageformat/JPEG) kaydetme işlemini etkiler; diğer tüm biçimler için yoksayılır. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Görüntüyü belirtilen biçimde ve kalitede bir akışa kaydeder.


```python
def save(self, stream, format, quality):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Görüntünün kaydedileceği akış. |
| format | [`ImageFormat`](/slides/python-net/tr/aspose.slides/imageformat) | Görüntü biçimi. |
| quality | **int** | Kaydedilen görüntünün kalitesi (0 ile 100 arasında).  <br/><br/>            Bu parametre yalnızca [`ImageFormat.JPEG`](/slides/python-net/tr/aspose.slides/imageformat/JPEG) kaydetme işlemini etkiler; diğer tüm biçimler için yoksayılır. |



### Ayrıca Bakınız
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* enumerasyon [`ImageFormat`](/slides/python-net/tr/aspose.slides/imageformat)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)