---
title: set_EmbedImages()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает параметр встраивания изображений. Принимает bool.
type: docs
weight: 66
url: /ru/aspose.slides.export/ihtml5options/set_embedimages/
---
## IHtml5Options::set_EmbedImages(bool) метод


Устанавливает параметр встраивания изображений. Принимает **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_EmbedImages(bool value)=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## См. также

* Класс [IHtml5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)