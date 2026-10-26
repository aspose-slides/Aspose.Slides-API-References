---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Referansı
description: Metinlerin bağlamaları (ligature) kullanmadan render edilip edilmediğini gösteren bir değer alır. true olarak ayarlandığında, bağlamalar render çıktısında devre dışı bırakılır. Varsayılan olarak, bu özellik false olarak ayarlanmıştır.
type: docs
weight: 326
url: /tr/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() metodu

Metinlerin bağlamaları (ligature) kullanmadan render edilip edilmediğini gösteren bir değeri alır. **true** olarak ayarlandığında, bağlamalar render çıktısında devre dışı bırakılır. Varsayılan olarak, bu özellik **false** olarak ayarlanmıştır.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Metin render'ında bağlamaları devre dışı bırak

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Ayrıca Bakınız

* Sınıf [ISVGOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)