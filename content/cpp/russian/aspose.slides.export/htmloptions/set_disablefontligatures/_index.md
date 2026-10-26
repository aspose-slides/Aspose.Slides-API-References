---
title: set_DisableFontLigatures()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает значение, указывающее, будет ли текст отображаться без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство установлено в false.
type: docs
weight: 105
url: /ru/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) метод


Устанавливает значение, указывающее, будет ли текст отображаться без использования лигатур. При установке в **true** лигатуры будут отключены в выводе. По умолчанию это свойство установлено в **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Примечания


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