---
title: set_DisableFontLigatures()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает значение, указывающее, будет ли текст отображаться без использования лигатур. При значении true лигатуры будут отключены в выводе. По умолчанию это свойство установлено в false.
type: docs
weight: 118
url: /ru/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) метод

Устанавливает значение, указывающее, будет ли текст отображаться без использования лигатур. Если установлено в **true**, лигатуры будут отключены в выводе. По умолчанию это свойство установлено в **false**.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Отключить лигатуры при отображении текста

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Смотрите также

* Класс [Html5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)