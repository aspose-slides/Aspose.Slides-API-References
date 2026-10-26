---
title: get_OutputPath()
second_title: Справочник API Aspose.Slides для C++
description: "Определяет, где должны храниться внешние ресурсы. Читайте System::String."
type: docs
weight: 79
url: /ru/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() метод

Определяет, где должны храниться внешние ресурсы. Читать [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
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

## См. также

* Класс [String](../../../system/string/)
* Класс [Html5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)