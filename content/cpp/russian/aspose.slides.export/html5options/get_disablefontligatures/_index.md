---
title: get_DisableFontLigatures()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает значение, указывающее, отображается ли текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение false.
type: docs
weight: 105
url: /ru/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() метод

Возвращает значение, указывающее, отображается ли текст без использования лигатур. Когда установлено значение **true**, лигатуры будут отключены в результирующем выводе. По умолчанию это свойство имеет значение **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Отключить лигатуры при отображении текста

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## См. также

* Класс [Html5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)