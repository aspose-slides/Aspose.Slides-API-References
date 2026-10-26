---
title: get_DisableFontLigatures()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke false.
type: docs
weight: 183
url: /id/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() metode


Mendapatkan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke **true**, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
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

* Kelas [IHtmlOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)