---
title: get_OutputPath()
second_title: Справочник API Aspose.Slides для C++
description: "Определяет, где следует сохранять внешние ресурсы. Читайте System::String."
type: docs
weight: 79
url: /ru/aspose.slides.export/ihtml5options/get_outputpath/
---
## IHtml5Options::get_OutputPath() метод

Определяет, где следует хранить внешние ресурсы. Читайте [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::IHtml5Options::get_OutputPath()=0
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## См. также

* Класс [String](../../../system/string/)
* Класс [IHtml5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)