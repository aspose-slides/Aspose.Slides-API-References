---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Referansı
description: Metnin ligatürler kullanılmadan işlenip işlenmediğini gösteren bir değer ayarlar. true olarak ayarlandığında, ligatürler işlenmiş çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik false olarak ayarlanır.
type: docs
weight: 144
url: /tr/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) metod

Metin ligatürler kullanılmadan işlenip işlenmediğini belirten bir değer ayarlar. **true** olarak ayarlandığında, ligatürler işlenmiş çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik **false** olarak ayarlanır.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Metin işleme sırasında ligatürleri devre dışı bırak

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Ayrıca Bakınız

* Sınıf [Html5Options](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)