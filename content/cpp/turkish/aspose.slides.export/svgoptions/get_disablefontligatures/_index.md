---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Referansı
description: Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değer alır. true olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılır. Varsayılan olarak, bu özellik false olarak ayarlanmıştır.
type: docs
weight: 326
url: /tr/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() yöntemi

Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değer alır. **true** olarak ayarlandığında, render edilen çıktı içinde ligatürler devre dışı bırakılır. Varsayılan olarak, bu özellik **false** olarak ayarlanmıştır.

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
```

## Açıklamalar

Örnek:

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Metin render'ında ligatürleri devre dışı bırak

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Ayrıca Bakınız

* Sınıf [SVGOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)