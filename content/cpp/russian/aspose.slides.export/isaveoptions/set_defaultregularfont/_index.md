---
title: set_DefaultRegularFont()
second_title: Aspose.Slides для C++ справочник API
description: "Устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Записывает System::String."
type: docs
weight: 66
url: /ru/aspose.slides.export/isaveoptions/set_defaultregularfont/
---
## ISaveOptions::set_DefaultRegularFont(System::String) метод


Устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Записывает [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_DefaultRegularFont(System::String value)=0
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
* Класс [ISaveOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)