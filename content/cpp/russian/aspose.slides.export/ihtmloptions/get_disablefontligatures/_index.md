---
title: get_DisableFontLigatures()
second_title: Aspose.Slides для C++ справки по API
description: Получает значение, указывающее, рендерится ли текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство установлено в false.
type: docs
weight: 183
url: /ru/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() метод


Получает значение, указывающее, рендерится ли текст без использования лигатур. Когда установлено в **true**, лигатуры будут отключены в выводе. По умолчанию это свойство установлено в **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Отключить лигатуры при рендеринге текста

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## См. также

* Класс [IHtmlOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)