---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Referansı
description: Metnin ligatürler kullanılmadan işlenip işlenmediğini gösteren bir değer alır. **true** olarak ayarlandığında, ligatürler işlenmiş çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik **false** olarak ayarlanmıştır.
type: docs
weight: 92
url: /tr/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() metod

Metin, ligatürler kullanılmadan işlenip işlenmediğini gösteren bir değer alır. **true** olarak ayarlandığında, çıktıda ligatürler devre dışı bırakılır. Varsayılan olarak, bu özellik **false** olarak ayarlanmıştır.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## Açıklamalar

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Metin işleme sırasında ligatürleri devre dışı bırak

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Ayrıca Bakınız

* Sınıf [HtmlOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)