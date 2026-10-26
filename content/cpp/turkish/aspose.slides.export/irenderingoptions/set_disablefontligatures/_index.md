---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Referansı
description: Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri ayarlar. true olarak ayarlandığında, render edilen çıktıda ligatürler devre dışı bırakılır. Varsayılan olarak, bu özellik false olarak ayarlanır.
type: docs
weight: 53
url: /tr/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) metot


Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri ayarlar. **true** olarak ayarlandığında, render edilen çıktıda ligatürler devre dışı bırakılır. Varsayılan olarak, bu özellik **false** olarak ayarlanır.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
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

* Sınıf [IRenderingOptions](../)
* Ad Alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)