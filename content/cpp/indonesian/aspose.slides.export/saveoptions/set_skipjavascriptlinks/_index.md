---
title: set_SkipJavaScriptLinks()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah akan melewati hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Tulis bool. Nilai default adalah false.
type: docs
weight: 118
url: /id/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) metode

Menentukan apakah akan melewati hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Tulis **bool**. Nilai default adalah **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Catatan

Ketika properti ini diatur ke **true**, hyperlink dengan panggilan JavaScript akan diabaikan saat menyimpan.

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
* Library [Aspose.Slides](../../../)