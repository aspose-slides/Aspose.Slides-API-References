---
title: get_EmbedImages()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает параметр встраивания изображений. Чтение bool.
type: docs
weight: 53
url: /ru/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() метод


Возвращает параметр встраивания изображений. Чтение **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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

* Класс [Html5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)