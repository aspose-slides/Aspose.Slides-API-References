---
title: Compress class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.lowcode/compress/
---
## Compress sınıfı

[`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı sıkıştırmak için tasarlanmış bir grup yöntemi temsil eder.

Compress türü aşağıdaki üyeleri sunar:

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/tr/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Sunumun boyutunu, mevcut tüm sıkıştırma adımlarını uygulayarak azaltır:<br/>            <br/>* Kullanılmayan ana slaytları kaldırır **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Kullanılmayan yerleşim slaytlarını kaldırır **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Gömülü yazı tiplerinde gerçekten kullanılan glifleri tutar **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Resim çözünürlüğünü 150 DPI'ye düşürür ve resimlerin kırpılmış alanlarını siler **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/tr/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı kullanılmayan ana slaytları kaldırarak sıkıştırır. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/tr/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı kullanılmayan yerleşim slaytlarını kaldırarak sıkıştırır. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/tr/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)'ı gömülü yazı tiplerinden kullanılmayan karakterleri kaldırarak sıkıştırır. |
| [`compress_images(presentation, resolution)`](/slides/python-net/tr/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Sunumdaki resimlerin çözünürlüğünü azaltır ve kırpılmış alanlarını siler,<br/>            PowerPoint'in "Resimleri Sıkıştır" özelliğine benzer şekilde tüm resimlere uygulanır.<br/>            Slaytlardaki, yerleşim slaytlarındaki ve ana slaytlardaki resimler işlenir; grup şekillerinin içindeki resimler ve şekillerin resim doldurmaları da dahil. |

### Diğer
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* modül [`aspose.slides.lowcode`](/slides/python-net/tr/aspose.slides.lowcode)
* kütüphane [`Aspose.Slides`](/slides/python-net)