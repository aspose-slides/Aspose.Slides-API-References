---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API Referansı
description: Fırça oluşturulurken ROP işlemi veya Opacity kullanır.
type: docs
weight: 27
url: /tr/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() metodu

Fırça oluşturulurken ROP işlemi veya Opacity kullanılır.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Açıklamalar

Varsayılan değer true'dur.

Sonraki örnek, [Ink](../../../aspose.slides.ink/) öğelerini dışa aktarırken ROP kullanarak nasıl ayarlanacağını gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ayrıca Bakınız

* Sınıf [IInkOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)