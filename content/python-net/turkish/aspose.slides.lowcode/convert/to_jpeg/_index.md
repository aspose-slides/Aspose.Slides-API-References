---
title: to_jpeg method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Giriş sunumunu JPEG formatında bir dizi görüntüye dönüştürür.  
            Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, 
            sonuç "myPath/myFilename_N.jpeg" dosyaları olarak kaydedilir, burada N bir slayt numarasıdır.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
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


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Giriş sunumunu JPEG formatında bir dizi görüntüye dönüştürür.  
            Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, 
            sonuç "myPath/myFilename_N.jpeg" dosyaları olarak kaydedilir, burada N bir slayt numarasıdır.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Giriş sunumu |
| output_file_name | **str** | Çıktı dosya adı. |
| image_size | [`Size`](/slides/python-net/tr/aspose.slides/size) | Her oluşturulan görüntünün boyutu. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Giriş sunumunu JPEG formatında bir dizi görüntüye dönüştürür.  
            Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, 
            sonuç "myPath/myFilename_N.jpeg" dosyaları olarak kaydedilir, burada N bir slayt numarasıdır.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Giriş sunumu. |
| output_file_name | **str** | Çıktı dosya adı. |
| scale | **float** | Orijinal slayt boyutuna göre çıktı görüntülerine uygulanan ölçek faktörü. |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Render seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Bakınız
* sınıf [`Convert`](/slides/python-net/tr/aspose.slides.lowcode/convert)
* sınıf [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions)
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* sınıf [`Size`](/slides/python-net/tr/aspose.slides/size)
* modül [`aspose.slides.lowcode`](/slides/python-net/tr/aspose.slides.lowcode)
* kütüphane [`Aspose.Slides`](/slides/python-net)