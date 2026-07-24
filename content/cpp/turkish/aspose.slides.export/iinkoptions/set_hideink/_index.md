---
title: set_HideInk()
second_title: Aspose.Slides for C++ API Referansı
description: Dışa aktarılan belgede Ink öğelerini gösterir veya gizler.
type: docs
weight: 14
url: /tr/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) metod


Dışa aktarılan belgede [Ink](../../../aspose.slides.ink/) öğelerini gösterir veya gizler.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## Açıklamalar


Varsayılan değer false'tur. 

Aşağıdaki örnek, dışa aktarılan PDF belgesinde [Ink](../../../aspose.slides.ink/) öğelerini nasıl gizleyeceğinizi gösterir: 
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