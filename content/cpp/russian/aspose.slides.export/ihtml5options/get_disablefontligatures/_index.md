---
title: get_DisableFontLigatures()
second_title: Aspose.Slides для C++ справочник API
description: Получает значение, указывающее, будет ли текст отображаться без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение false.
type: docs
weight: 105
url: /ru/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() метод

Получает значение, указывающее, будет ли текст отображаться без использования лигатур. Когда установлено **true**, лигатуры будут отключены в выводе. По умолчанию это свойство установлено в **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## Замечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Отключить лигатуры в отображении текста

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## См. также

* Класс [IHtml5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)