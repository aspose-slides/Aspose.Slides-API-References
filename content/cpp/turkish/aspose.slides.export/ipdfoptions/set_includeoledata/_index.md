---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumdaki tüm OLE verilerini sonuç PDF'inde gömülü dosyalara dönüştürmek için true. bool yazın.
type: docs
weight: 469
url: /tr/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) yöntemi


True to convert all OLE data from the presentation to embedded files in the resulting PDF. Write **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
```

## Açıklamalar


Varsayılan **false**. 

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Diğer

* Sınıf [IPdfOptions](../)
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)