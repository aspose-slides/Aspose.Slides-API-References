---
title: get_DisableFontLigatures()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke false.
type: docs
weight: 131
url: /id/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() metode


Mengembalikan nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika disetel ke **true**, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini disetel ke **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Keterangan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Nonaktifkan ligatur dalam perenderan teks

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Lihat Juga

* Kelas [Html5Options](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)