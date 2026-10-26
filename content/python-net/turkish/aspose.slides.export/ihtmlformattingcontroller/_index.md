---
title: IHtmlFormattingController class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController sınıf

html dosyasının oluşturulmasını kontrol eder.

IHtmlFormattingController türü aşağıdaki üyeleri sunar:

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/tr/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | html belge başlığını yazmak için çağrılır. Sunum dönüştürmesi başına bir kez çağrılır. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/tr/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | html belge alt bilgisini yazmak için çağrılır. Sunum dönüştürmesi başına bir kez çağrılır. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/tr/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | html slayt başlığını yazmak için çağrılır. Her slayt başına bir kez çağrılır. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/tr/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | html slayt alt bilgisini yazmak için çağrılır. Her slayt başına bir kez çağrılır. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/tr/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Şekil çizilmeden önce çağrılır. Her şekil başına bir kez çağrılır. Bu işlev jeneratöre bir şey yazarsa, mevcut slayt görüntüsü oluşturma tamamlanır, ek html parçacığı eklenir ve yeni görüntü öncekinin üzerine başlatılır. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/tr/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Şekil çizilmeden önce çağrılır. Her şekil başına bir kez çağrılır. Bu işlev jeneratöre bir şey yazarsa, mevcut slayt görüntüsü oluşturma tamamlanır, ek html parçacığı eklenir ve yeni görüntü öncekinin üzerine başlatılır. |

### Ayrıca Bakınız
* modül [`aspose.slides.export`](/slides/python-net/tr/aspose.slides.export)
* kütüphane [`Aspose.Slides`](/slides/python-net)