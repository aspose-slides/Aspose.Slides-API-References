---
title: to_png method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Giriş sunumunu PNG formatında bir dizi görüntüye dönüştürür.  
            Çıktı dosya adı “myPath/myFilename.png” olarak verilirse,  
            sonuç “myPath/myFilename_N.png” dosyaları şeklinde kaydedilir, burada N bir slayt numarasıdır.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Giriş sunumu. |
| output_file_name | **str** | Çıktı dosya adı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Giriş sunumunu PNG formatında bir dizi görüntüye dönüştürür.  
            Çıktı dosya adı “myPath/myFilename.png” olarak verilirse,  
            sonuç “myPath/myFilename_N.png” dosyaları şeklinde kaydedilir, burada N bir slayt numarasıdır.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Giriş sunumu |
| output_file_name | **str** | Çıktı dosya adı. |
| image_size | [`Size`](/slides/python-net/tr/aspose.slides/size) | Oluşturulan her görüntünün boyutu. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Giriş sunumunu PNG formatında bir dizi görüntüye dönüştürür.  
            Çıktı dosya adı “myPath/myFilename.png” olarak verilirse,  
            sonuç “myPath/myFilename_N.png” dosyaları şeklinde kaydedilir, burada N bir slayt numarasıdır.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Giriş sunumu. |
| output_file_name | **str** | Çıktı dosya adı. |
| scale | **float** | Çıktı görüntülerine orijinal slayt boyutuna göre uygulanan ölçekleme faktörü. |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Render seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Ayrıca Bakınız
* sınıf [`Convert`](/slides/python-net/tr/aspose.slides.lowcode/convert)
* sınıf [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions)
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* sınıf [`Size`](/slides/python-net/tr/aspose.slides/size)
* modül [`aspose.slides.lowcode`](/slides/python-net/tr/aspose.slides.lowcode)
* kütüphane [`Aspose.Slides`](/slides/python-net)