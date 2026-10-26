---
title: set_DefaultRegularFont()
second_title: Aspose.Slides untuk Referensi API C++
description: "Mengatur font yang digunakan bila font sumber tidak ditemukan. Menulis System::String."
type: docs
weight: 66
url: /id/aspose.slides.export/saveoptions/set_defaultregularfont/
---
## SaveOptions::set_DefaultRegularFont(System::String) metode


Mengatur font yang digunakan jika font sumber tidak ditemukan. Menulis [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::SaveOptions::set_DefaultRegularFont(System::String value) override
```

## Catatan



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto htmlOpts = System::MakeObject<HtmlOptions>();
htmlOpts->set_DefaultRegularFont(u"Arial Black");
pres->Save(u"SomePresentation-out-ArialBlack.html", Aspose::Slides::Export::SaveFormat::Html, htmlOpts);
htmlOpts->set_DefaultRegularFont(u"Lucida Console");
pres->Save(u"Somepresentation-out-LucidaConsole.html", Aspose::Slides::Export::SaveFormat::Html, htmlOpts);

auto pdfOpts = System::MakeObject<PdfOptions>();
pdfOpts->set_DefaultRegularFont(u"Arial Black");
pres->Save(u"SomePresentation-out-ArialBlack.pdf", Aspose::Slides::Export::SaveFormat::Pdf, pdfOpts);
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [SaveOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)