---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API Referansı
description: Fırça renderleme için ROP işlemi veya Opacity kullanır.
type: docs
weight: 40
url: /tr/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) metodu

Fırçayı renderlemek için ROP işlemi veya Opacity kullanır.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Açıklamalar

Varsayılan değer true'dur.

Sonraki örnek, [Ink](../../../aspose.slides.ink/) öğeleri dışa aktarırken ROP kullanarak nasıl ayarlanacağını gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Diğer

* Class [IInkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)