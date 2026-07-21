---
title: MarkdownSvgImageSavingHandler
second_title: Справочник API Aspose.Slides для C++
description: Вызывается для каждого SVG-изображения при экспорте Markdown. Верните true, чтобы использовать указанный link, или false, чтобы применить логику сохранения по умолчанию.
type: docs
weight: 313
url: /ru/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef


Вызывается для каждого SVG-изображения при экспорте Markdown. 

 Верните **true**, чтобы использовать указанный *link* , 

 или **false**, чтобы применить логику сохранения по умолчанию.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```


## См. также

* Класс [MarkdownSaveOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)