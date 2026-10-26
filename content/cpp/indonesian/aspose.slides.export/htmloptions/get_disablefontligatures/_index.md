---
title: get_DisableFontLigatures()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika diatur ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke false.
type: docs
weight: 92
url: /id/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() metode

Mengambil nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika diatur ke **true**, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## Keterangan

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Nonaktifkan ligatur dalam perenderan teks

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Lihat Juga

* Kelas [HtmlOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)