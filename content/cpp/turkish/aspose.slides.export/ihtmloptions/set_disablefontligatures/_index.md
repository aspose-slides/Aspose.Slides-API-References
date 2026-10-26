---
title: set_DisableFontLigatures()
second_title: Aspose.Slides için C++ API Referansı
description: Metnin ligatürler kullanılmadan render edilip edilmediğini belirten bir değer ayarlar. true olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanır.
type: docs
weight: 196
url: /tr/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) metod

Metnin ligatürler kullanılmadan render edilip edilmediğini belirten bir değer ayarlar. **true** olarak ayarlandığında, ligatürler render edilmiş çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik **false** olarak ayarlanır.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Metin render işleminde ligatürleri devre dışı bırak

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Ayrıca Bakınız

* Sınıf [IHtmlOptions](../)
* İsim Uzayı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)