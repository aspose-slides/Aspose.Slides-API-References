---
title: set_DisableFontLigatures()
second_title: Aspose.Slides C++ için API Referansı
description: Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değer ayarlar. true olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılacaktır. Varsayılan olarak, bu özellik false olarak ayarlanır.
type: docs
weight: 339
url: /tr/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) metot


Metin ligatürler kullanılmadan render edildiğini gösteren bir değer ayarlar. **true** olarak ayarlandığında, ligatürler render edilmiş çıktıda devre dışı bırakılacaktır. Varsayılan olarak, bu özellik **false** olarak ayarlanmıştır.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Metin render etme sırasında ligatürleri devre dışı bırak

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## İlgili

* Sınıf [SVGOptions](../)
* AdAlanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)