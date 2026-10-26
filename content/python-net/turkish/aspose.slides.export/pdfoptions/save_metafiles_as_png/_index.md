---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png özelliği
True, bir sunumda kullanılan tüm metafile'leri PNG görüntülerine dönüştürmek için.
            Okunur/Yazılır **bool**.


### Açıklamalar

Varsayılan **true** .
            Pdf belgesi vektör grafikler ve raster görüntüler içerebilir. 
            Eğer SaveMetafilesAsPng true olarak ayarlanırsa, kaynak Metafile 
            görüntüsü Png formatına dönüştürülür ve Pdf'ye raster 
            görüntü olarak kaydedilir. Eğer SaveMetafilesAsPng false olarak ayarlanırsa, kaynak Metafile 
            Pdf vektör grafiklerine dönüştürülür. Her iki yaklaşımın da avantajları 
            ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürüldüğünde, 
            sonucu belge ölçeklendirilirken bazı kalite kayıpları olabilir. Eğer Metafile Pdf vektör grafiklerine dönüştürülürse, 
            Pdf görüntüleme aracında performans sorunları olabilir.

### Tanım:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### Ayrıca Bakınız
* sınıf [`PdfOptions`](/slides/python-net/tr/aspose.slides.export/pdfoptions)
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)