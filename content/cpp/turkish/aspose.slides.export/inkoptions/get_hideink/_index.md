---
title: get_HideInk()
second_title: Aspose.Slides for C++ API Referansı
description: Dışa aktarılan belgede Ink öğelerini gösterir veya gizler.
type: docs
weight: 1
url: /tr/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() metodu


Gösterir veya gizler [Ink](../../../aspose.slides.ink/) elemanları dışa aktarılan belgede.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Açıklamalar


Varsayılan değer false'tur. 

Sonraki örnek, dışa aktarılan PDF belgesinde [Ink](../../../aspose.slides.ink/) elemanlarını nasıl gizleyeceğinizi gösterir: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ayrıca Bakınız

* Sınıf [InkOptions](../)
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)