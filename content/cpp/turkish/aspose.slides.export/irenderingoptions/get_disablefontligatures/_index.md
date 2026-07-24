---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API Referansı
description: Metnin ligatürler kullanılmadan işlenip işlenmediğini gösteren bir değer alır. true olarak ayarlandığında, ligatürler oluşturulan çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik false olarak ayarlanır.
type: docs
weight: 40
url: /tr/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() metodu


Metinlerin ligatürler kullanılmadan işlenip işlenmediğini belirten bir değer alır. **true** olarak ayarlandığında, ligatürler oluşturulan çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik **false** olarak ayarlanır.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## Açıklamalar


Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Metin işleme sırasında ligatürleri devre dışı bırak

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## İlgili

* Sınıf [IRenderingOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)