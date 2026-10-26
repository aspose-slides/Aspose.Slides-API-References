---
title: get_DisableFontLigatures()
second_title: Aspose.Slides для C++: справочник API
description: Получает значение, указывающее, отображается ли текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение false.
type: docs
weight: 92
url: /ru/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() метод


Возвращает значение, указывающее, отображается ли текст без использования лигатур. При установке в **true** лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## Примечание


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Отключить лигатуры при отображении текста

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## См. также

* Класс [HtmlOptions](../)
* Пространство имен [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)