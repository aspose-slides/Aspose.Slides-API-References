---
title: to_jpeg method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Girdi sunumunu bir dizi JPEG formatında görüntüye dönüştürür.  
            Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Girdi sunumu. |
| output_file_name | **str** | Çıktı dosya adı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Girdi sunumunu bir dizi JPEG formatında görüntüye dönüştürür.  
            Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Girdi sunumu |
| output_file_name | **str** | Çıktı dosya adı. |
| image_size | **aspose.slides.Size** | Oluşturulan her bir görüntünün boyutu. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Girdi sunumunu bir dizi JPEG formatında görüntüye dönüştürür.  
            Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları şeklinde kaydedilir; N bir slayt numarasıdır.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Girdi sunumu. |
| output_file_name | **str** | Çıktı dosya adı. |
| scale | **float** | Çıktı görüntülerine, orijinal slayt boyutuna göre uygulanan ölçekleme faktörü. |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Renderleme seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Ayrıca Bakınız
* sınıf [`Convert`](/slides/python-net/tr/aspose.slides.lowcode/convert)
* sınıf [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions)
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* modül [`aspose.slides.lowcode`](/slides/python-net/tr/aspose.slides.lowcode)
* kütüphane [`Aspose.Slides`](/slides/python-net)