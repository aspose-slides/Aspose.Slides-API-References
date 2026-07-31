---
title: get_DisableFontLigatures()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke false.
type: docs
weight: 40
url: /id/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() metode

Mendapatkan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke **true**, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke **false**.

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## Keterangan

Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Nonaktifkan ligatur dalam rendering teks

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Lihat Juga

* Kelas [RenderingOptions](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)