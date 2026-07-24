---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumdaki tüm OLE verilerini sonuç PDF'de gömülü dosyalara dönüştürmek için true. bool okunur.
type: docs
weight: 456
url: /tr/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() metodu

True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
```

## Açıklamalar

Default is **false**. 

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Ayrıca Bak

* Sınıf [IPdfOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)