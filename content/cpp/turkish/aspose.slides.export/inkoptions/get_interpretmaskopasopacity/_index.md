---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides için C++ API Referansı
description: Fırça oluşturulurken ROP işlemi veya Opacity kullanılır.
type: docs
weight: 27
url: /tr/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() metodu


Fırça oluşturulurken ROP işlemi veya Opacity kullanılır.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Açıklamalar


Varsayılan değer true'dur. 

Sonraki örnek, [Ink](../../../aspose.slides.ink/) öğelerini dışa aktarmak için ROP kullanarak nasıl ayarlandığını gösterir: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Diğer Bağlantılar

* Sınıf [InkOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)