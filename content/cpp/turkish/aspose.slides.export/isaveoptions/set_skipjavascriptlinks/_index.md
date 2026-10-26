---
title: set_SkipJavaScriptLinks()
second_title: C++ için Aspose.Slides API Referansı
description: Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirtir. bool yazın. Varsayılan değer false'tur.
type: docs
weight: 118
url: /tr/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) metod

Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirtir. **bool** yazın. Varsayılan değer **false**'tür.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## Açıklamalar

Bu özellik **true** olarak ayarlandığında, JavaScript çağrıları içeren köprüler kaydedilirken yoksayılacaktır.

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
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)