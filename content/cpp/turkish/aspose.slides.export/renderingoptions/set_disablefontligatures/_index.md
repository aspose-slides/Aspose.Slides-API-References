---
title: set_DisableFontLigatures()
second_title: Aspose.Slides için C++ API Referansı
description: Metnin ligatürler kullanılmadan render edilip edilmediğini belirten bir değer ayarlar. true olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılacaktır. Varsayılan olarak bu özellik false olarak ayarlanmıştır.
type: docs
weight: 53
url: /tr/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) metod

Metnin ligatürler kullanılmadan render edilip edilmediğini belirten bir değer ayarlar. **true** olarak ayarlandığında, ligatürler render edilen çıktıda devre dışı bırakılacaktır. Varsayılan olarak bu özellik **false** olarak ayarlanmıştır.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
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
* İsim Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)