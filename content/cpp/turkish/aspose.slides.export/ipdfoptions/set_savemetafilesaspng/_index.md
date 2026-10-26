---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides C++ API Referansı
description: True, bir sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için. bool yazın.
type: docs
weight: 300
url: /tr/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) metot

True, bir sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürmek için. **bool** yazın.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Açıklamalar

Default is **true**. Pdf belgesi vektör grafikleri ve raster görüntüler içerebilir. SaveMetafilesAsPng true olarak ayarlanırsa, kaynak Metafile görüntüsü Png formatına dönüştürülür ve Pdf'e raster görüntü olarak kaydedilir. SaveMetafilesAsPng false olarak ayarlanırsa, kaynak Metafile Pdf vektör grafiğine dönüştürülür. Her iki yaklaşımın da avantajları ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürülürse, ortaya çıkan belgenin ölçeklendirilmesi sırasında bazı kalite kayıpları olabilir. Metafile Pdf vektör grafiğine dönüştürülürse, Pdf görüntüleme aracında performans sorunları ortaya çıkabilir.

## İlgili

* Sınıf [IPdfOptions](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)