---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController sınıfı

WOFF biçiminde tüm sunum yazı tiplerini gömmek için kullanılacak biçimlendirme denetleyici sınıfı.

EmbedAllFontsHtmlController türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Yeni bir örnek oluşturur |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Yeni bir örnek oluşturur |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | HTML belge başlığını yazmak için çağrılır. Sunum dönüşümü başına bir kez çağrılır. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | HTML belge altbilgisini yazmak için çağrılır. Sunum dönüşümü başına bir kez çağrılır. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | HTML slayt başlığını yazmak için çağrılır. Her slayt için bir kez çağrılır. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | HTML slayt altbilgisini yazmak için çağrılır. Her slayt için bir kez çağrılır. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Şeklin işlenmesinden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev oluşturucuya herhangi bir şey yazarsa, mevcut slayt görüntüsü oluşturma tamamlanacak, ek HTML parçacığı eklenecek ve yeni görüntü öncekinin üzerine başlatılacaktır. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Şeklin işlenmesinden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev oluşturucuya herhangi bir şey yazarsa, mevcut slayt görüntüsü oluşturma tamamlanacak, ek HTML parçacığı eklenecek ve yeni görüntü öncekinin üzerine başlatılacaktır. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) içinde bulunan tüm yazı tiplerini yazar. |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/tr/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Verileri base64 olarak doğrudan HTML belgesine yazar |

### Ayrıca Bakınız
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)