---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumdan tüm OLE verilerini ortaya çıkan PDF'de gömülü dosyalara dönüştürmek için true. bool yazın.
type: docs
weight: 469
url: /tr/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) metod

Sunumdan tüm OLE verilerini çıkan PDF'de gömülü dosyalara dönüştürmek için true. **bool** yazın.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## Açıklamalar

Varsayılan **false**'dur. 

Örnek: 

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Ayrıca Bakınız

* Sınıf [PdfOptions](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)