---
title: get_EmbedImages()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает параметр встраивания изображений. Читает **bool**.
type: docs
weight: 53
url: /ru/aspose.slides.export/ihtml5options/get_embedimages/
---
## IHtml5Options::get_EmbedImages() метод

Возвращает параметр встраивания изображений. Читает **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_EmbedImages()=0
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## Смотрите также

* Класс [IHtml5Options](../)
* Пространство имен [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)