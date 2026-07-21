---
title: MarkdownImageSavingHandler
second_title: Справочник API Aspose.Slides для C++
description: Вызывается для каждого не-SVG изображения (bitmap или metafile) во время экспорта Markdown.  Верните true, чтобы использовать указанный link ,  или false, чтобы применить логику сохранения по умолчанию.
type: docs
weight: 300
url: /ru/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef


Вызывается для каждого не-SVG изображения (bitmap или metafile) во время экспорта Markdown. 

 Верните **true**, чтобы использовать указанный *ссылка* , 

 или **false**, чтобы применить логику сохранения по умолчанию.

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## См. также

* Класс [MarkdownSaveOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)