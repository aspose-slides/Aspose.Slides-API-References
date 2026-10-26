---
title: get_DisableFontLigatures()
second_title: Referensi API Aspose.Slides untuk C++ 
description: Mengambil nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara bawaan, properti ini disetel ke false.
type: docs
weight: 131
url: /id/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() metode

Mendapatkan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke **true**, ligatur akan dinonaktifkan dalam output yang dirender. Secara bawaan, properti ini disetel ke **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## Catatan

Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Nonaktifkan ligatur dalam rendering teks

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Lihat Juga

* Kelas [IHtml5Options](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)