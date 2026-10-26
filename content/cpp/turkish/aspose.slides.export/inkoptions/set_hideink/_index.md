---
title: set_HideInk()
second_title: Aspose.Slides için C++ API Referansı
description: Dışa aktarılan belgede Ink öğelerini gösterir veya gizler.
type: docs
weight: 14
url: /tr/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) metot

Dışa aktarılan belgede [Ink](../../../aspose.slides.ink/) öğelerini gösterir veya gizler.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Açıklamalar

Öntanımlı değer false'tur. 

Sonraki örnek, dışa aktarılan PDF belgesinde [Ink](../../../aspose.slides.ink/) öğelerini nasıl gizleyeceğinizi gösterir: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Bakınız

* Sınıf [InkOptions](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)