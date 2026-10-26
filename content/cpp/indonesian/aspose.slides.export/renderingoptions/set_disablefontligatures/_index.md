---
title: set_DisableFontLigatures()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika diatur ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke false.
type: docs
weight: 53
url: /id/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) metode

Mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika diatur ke **true**, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## Keterangan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Nonaktifkan ligatur dalam perenderan teks

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Lihat Juga

* Kelas [RenderingOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)