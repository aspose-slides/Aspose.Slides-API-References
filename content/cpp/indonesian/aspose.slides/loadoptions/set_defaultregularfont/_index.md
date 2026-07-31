---
title: set_DefaultRegularFont()
second_title: Aspose.Slides untuk Referensi API C++
description: "Menetapkan font Regular yang digunakan bila font sumber tidak ditemukan. Tulis System::String."
type: docs
weight: 40
url: /id/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) Metode

Menetapkan font Regular yang digunakan bila font sumber tidak ditemukan. Tulis [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Catatan

Contoh berikut menunjukkan cara mengatur font default untuk merender PowerPoint [Presentation](../../presentation/).
```cpp
// Gunakan opsi pemuatan untuk menentukan font regular dan Asian default
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Muat presentasi
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Buat thumbnail slide
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Buat PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Buat XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [LoadOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)