---
title: set_DisableFontLigatures()
second_title: Aspose.Slides için C++ API Referansı
description: Metnin ligatürler kullanılmadan işlenip işlenmediğini belirten bir değer ayarlar. true olarak ayarlandığında, ligatürler oluşturulan çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanır.
type: docs
weight: 105
url: /tr/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) metod

Metnin ligatürler kullanılmadan işlenip işlenmeyeceğini belirten bir değer ayarlar. **true** olarak ayarlandığında, ligatürler oluşturulan çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik **false** olarak ayarlıdır.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Açıklamalar

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Metin işlenirken ligatürleri devre dışı bırak

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Ayrıca Bakınız

* Sınıf [HtmlOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)