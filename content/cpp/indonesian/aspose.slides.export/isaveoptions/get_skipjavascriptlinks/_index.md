---
title: get_SkipJavaScriptLinks()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Baca bool. Nilai default adalah false.
type: docs
weight: 105
url: /id/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() metode

Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Baca **bool**. Nilai default adalah **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
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

* Class [ISaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)