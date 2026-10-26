---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides için C++ API Referansı
description: Fırça işleme sırasında ROP işlemi veya Opaklık kullanır.
type: docs
weight: 40
url: /tr/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) metod

Fırçayı işlerken ROP işlemi veya Opaklık kullanır.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## Açıklamalar

Varsayılan değer true'dur.

Sonraki örnek, [Ink](../../../aspose.slides.ink/) elemanlarını dışa aktarmak için ROP kullanarak nasıl ayarlanacağını gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## İlgili Bağlantılar

* Sınıf [InkOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)