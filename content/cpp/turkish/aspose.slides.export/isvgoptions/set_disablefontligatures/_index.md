---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Referansı
description: Metnin bağlamalar kullanılmadan render edilip edilmediğini gösteren bir değer ayarlar. true olarak ayarlandığında, bağlamalar oluşturulan çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanır.
type: docs
weight: 339
url: /tr/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISSVGOptions::set_DisableFontLigatures(bool) metod

Metnin bağlamalar kullanılmadan render edilip edilmediğini gösteren bir değer ayarlar. **true** olarak ayarlandığında, bağlamalar oluşturulan çıktıda devre dışı bırakılacaktır. Varsayılan olarak bu özellik **false** olarak ayarlanmıştır.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
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

## Bakınız

* Sınıf [ISVGOptions](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)