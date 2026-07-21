---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ Справочник API
description: Устанавливает значение, указывающее, отображается ли текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение false.
type: docs
weight: 118
url: /ru/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) метод


Устанавливает значение, указывающее, отображается ли текст без использования лигатур. При установке в **true**, лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение **false**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Отключить лигатуры при рендеринге текста

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Смотрите также

* Класс [IHtml5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)