---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png özelliği
True to convert all metafiles used in a presentation to the PNG images.
            Okuma/Yazma **bool**.


### Açıklamalar

Varsayılan **true** .
            Pdf belgesi vektör grafikleri ve raster görüntüler içerebilir. 
            Eğer SaveMetafilesAsPng true olarak ayarlanırsa, kaynak Metafile resmi Png formatına dönüştürülür ve Pdf'e raster görüntü olarak kaydedilir. Eğer SaveMetafilesAsPng false olarak ayarlanırsa, kaynak Metafile Pdf vektör grafiğine dönüştürülür. Her iki yaklaşımın da avantajları ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürülürse, ortaya çıkan belge ölçeklendirilirken bazı kalite kayıpları olabilir. Metafile Pdf vektör grafiğine dönüştürülürse, Pdf görüntüleme aracında performans sorunları oluşabilir.

### Tanım:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### İlgili Bakınız
* sınıf [`IPdfOptions`](/slides/python-net/tr/aspose.slides.export/ipdfoptions)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)