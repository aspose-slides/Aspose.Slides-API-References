---
title: get_SkipJavaScriptLinks()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah akan melewatkan hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. Baca bool. Nilai default adalah false.
type: docs
weight: 105
url: /id/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() method


Menentukan apakah akan melewatkan hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. Baca **bool**. Nilai default adalah **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Catatan


Ketika properti ini diatur ke **true**, hyperlink dengan pemanggilan JavaScript akan diabaikan saat menyimpan.

Ketika properti ini diatur ke **false**, semua hyperlink akan disimpan.

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Lihat Juga

* Kelas [SaveOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)