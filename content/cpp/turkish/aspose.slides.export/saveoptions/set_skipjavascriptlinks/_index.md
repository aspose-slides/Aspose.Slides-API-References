---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides için C++ API Referansı
description: Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir. Yazma türü bool. Varsayılan değer false.
type: docs
weight: 118
url: /tr/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) metod

Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirtir. Yazma türü **bool**. Varsayılan değer **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
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

## Bkz

* Sınıf [SaveOptions](../)
* İsim Uzayı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)