---
title: set_DisableFontLigatures()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika diatur ke true, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke false.
type: docs
weight: 105
url: /id/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) metode


Mengatur nilai yang menunjukkan apakah teks dirender tanpa menggunakan ligatur. Ketika diatur ke **true**, ligatur akan dinonaktifkan dalam output yang dirender. Secara default, properti ini diatur ke **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Nonaktifkan ligatur dalam perenderan teks

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Lihat Juga

* Kelas [HtmlOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Pustaka [Aspose.Slides](../../../)