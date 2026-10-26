---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir. bool okunur. Varsayılan değer false'tur.
type: docs
weight: 105
url: /tr/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() metodu

Sunumu kaydederken JavaScript çağrılarına sahip köprülerin atlanıp atlanmayacağını belirtir. **bool** okur. Varsayılan değer **false**'dır.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Açıklamalar

Bu özellik **true** olarak ayarlandığında, JavaScript çağrısı içeren köprüler kaydetme sırasında yoksayılır.

Bu özellik **false** olarak ayarlandığında, tüm köprüler kaydedilir.

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Ayrıca Bakınız

* Sınıf [SaveOptions](../)
* İsim Uzayı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)