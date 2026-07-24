---
title: get_HideInk()
second_title: Aspose.Slides for C++ API Referansı
description: Dışa aktarılan belgede Ink öğelerini gösterir veya gizler.
type: docs
weight: 1
url: /tr/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() method


Dışa aktarılan belgede [Ink](../../../aspose.slides.ink/) öğelerini gösterir veya gizler.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Açıklamalar


Varsayılan değer false'tur.

Sonraki örnek, dışa aktarılan PDF belgesinde [Ink](../../../aspose.slides.ink/) öğelerinin nasıl gizleneceğini gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ayrıca Bakınız

* Sınıf [IInkOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)