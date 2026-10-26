---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirtir. bool olarak okunur. Varsayılan değer false.
type: docs
weight: 105
url: /tr/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() metodu


Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirtir. **bool** olarak okunur. Varsayılan değer **false**’dır.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Açıklamalar


Bu özellik **true** olarak ayarlandığında, JavaScript çağrıları içeren köprüler kaydedilirken yok sayılacaktır.

Bu özellik **false** olarak ayarlandığında, tüm köprüler kaydedilecektir.

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Ayrıca Bakınız

* Sınıf [ISaveOptions](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)