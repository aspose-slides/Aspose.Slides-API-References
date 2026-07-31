---
title: get_DefaultRegularFont()
second_title: Aspose.Slides untuk Referensi API C++
description: "Mengembalikan font Regular yang digunakan jika font sumber tidak ditemukan. Baca System::String."
type: docs
weight: 27
url: /id/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() metode


Mengembalikan font Regular yang digunakan jika font sumber tidak ditemukan. Baca [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
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
// Hasilkan thumbnail slide
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Hasilkan PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Hasilkan XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [LoadOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)