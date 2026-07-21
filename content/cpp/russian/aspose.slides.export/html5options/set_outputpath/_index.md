---
title: set_OutputPath()
second_title: Справочник API Aspose.Slides для C++
description: "Определяет, где следует хранить внешние ресурсы. Запишите System::String."
type: docs
weight: 92
url: /ru/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) метод

Определяет, где следует хранить внешние ресурсы. Запишите [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [Html5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)