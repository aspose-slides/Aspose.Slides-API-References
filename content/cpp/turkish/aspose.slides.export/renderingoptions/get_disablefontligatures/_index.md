---
title: get_DisableFontLigatures()
second_title: Aspose.Slides için C++ API Referansı
description: Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değer döndürür. true olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanır.
type: docs
weight: 40
url: /tr/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() metodu

Metinlerin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değer döndürür. **true** olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılacaktır. Varsayılan olarak bu özellik **false** olarak ayarlıdır.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## Açıklamalar

Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Metin render'ında ligatürleri devre dışı bırak

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Ayrıca Bakınız

* Sınıf [RenderingOptions](../)
* İsim alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)