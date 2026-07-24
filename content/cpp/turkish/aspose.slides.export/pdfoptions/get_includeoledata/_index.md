---
title: get_IncludeOleData()
second_title: Aspose.Slides için C++ API Referansı
description: Sunumdaki tüm OLE verilerini sonuç PDF'de gömülü dosyalara dönüştürmek için true. Okunur bool.
type: docs
weight: 456
url: /tr/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() metodu

Sunumdaki tüm OLE verilerini sonuç PDF'de gömülü dosyalara dönüştürmek için true. Okunur **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Açıklama

Varsayılan **false**.  

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Bkz.

* Sınıf [PdfOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)