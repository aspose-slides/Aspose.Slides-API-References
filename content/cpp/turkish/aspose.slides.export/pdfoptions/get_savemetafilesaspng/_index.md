---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API Referansı
description: True, bir sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürür. bool okunur.
type: docs
weight: 326
url: /tr/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() metodu

True, bir sunumda kullanılan tüm metafile'ları PNG görüntülerine dönüştürür. **bool** türünde okunur.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Açıklamalar

Varsayılan **true** değeridir. Pdf belgesi vektör grafikleri ve raster görüntüler içerebilir. SaveMetafilesAsPng true olarak ayarlanırsa, kaynak Metafile görüntüsü Png formatına dönüştürülür ve Pdf'e raster görüntü olarak kaydedilir. SaveMetafilesAsPng false olarak ayarlanırsa, kaynak Metafile Pdf vektör grafikleri olarak dönüştürülür. Her iki yaklaşımın da avantajları ve dezavantajları vardır. Örneğin, Metafile PNG'ye dönüştürülürse, ortaya çıkan belge ölçeklendirilirken bazı kalite kayıpları yaşanabilir. Metafile Pdf vektör grafikleri olarak dönüştürülürse, Pdf görüntüleme aracında performans sorunları ortaya çıkabilir.

## Diğer Bağlantılar

* Sınıf [PdfOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)