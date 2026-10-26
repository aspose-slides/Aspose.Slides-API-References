---
title: to_tiff method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Giriş sunumunu TIFF formatında bir dizi görüntüye dönüştürür.  
            Çıktı dosya adı \"myPath/myFilename.tiff\" olarak verilirse, 
            sonuç \"myPath/myFilename_N.tiff\" dosyaları şeklinde kaydedilir; burada N bir slayt numarasıdır.


```python
@staticmethod
def to_tiff(pres, output_file_name):
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


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Giriş sunumunu özel seçeneklerle TIFF formatına dönüştürür.
            Çıktı dosya adı \"myPath/myFilename.tiff\" olarak verilirse ve `multipage` `false` ise, 
            sonuç \"myPath/myFilename_N.tiff\" dosyaları şeklinde kaydedilir; burada N bir slayt numarasıdır.
            Aksi takdirde, `multipage` `true` ise, sonuç çok sayfalı bir \"myPath/myFilename.tiff\" belgesi olur.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Giriş sunumu. |
| output_file_name | **str** | Çıktı dosya adı. |
| options | [`ITiffOptions`](/slides/python-net/tr/aspose.slides.export/itiffoptions) | TIFF kaydetme seçenekleri. |
| multipage | **bool** | Oluşturulan TIFF belgesinin çok sayfalı olup olmayacağını belirtir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### İlgili
* sınıf [`Convert`](/slides/python-net/tr/aspose.slides.lowcode/convert)
* sınıf [`ITiffOptions`](/slides/python-net/tr/aspose.slides.export/itiffoptions)
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* modül [`aspose.slides.lowcode`](/slides/python-net/tr/aspose.slides.lowcode)
* kütüphane [`Aspose.Slides`](/slides/python-net)