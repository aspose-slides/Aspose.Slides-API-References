---
title: set_EmbedImages()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает параметр встраивания изображений. Записывает bool.
type: docs
weight: 66
url: /ru/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) метод


Устанавливает параметр встраивания изображений. Записывает **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
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

* Класс [Html5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)