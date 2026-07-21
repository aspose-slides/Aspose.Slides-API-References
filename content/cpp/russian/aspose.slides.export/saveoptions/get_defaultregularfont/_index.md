---
title: get_DefaultRegularFont()
second_title: Aspose.Slides для C++ API Reference
description: "Возвращает шрифт, используемый в случае, если исходный шрифт не найден. Читает System::String."
type: docs
weight: 53
url: /ru/aspose.slides.export/saveoptions/get_defaultregularfont/
---
## SaveOptions::get_DefaultRegularFont() метод

Возвращает шрифт, используемый в случае, если исходный шрифт не найден. Читает [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::SaveOptions::get_DefaultRegularFont() override
```

## Примечания

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

## См. также

* Класс [String](../../../system/string/)
* Класс [SaveOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)