---
title: set_SlidesLayoutOptions()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает режим, в котором слайды размещаются на странице при экспорте презентации ISlidesLayoutOptions. Это свойство не поддерживает присваивание объектов типа Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 404
url: /ru/aspose.slides.export/iswfoptions/set_slideslayoutoptions/
---
## ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) метод

Задает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../islideslayoutoptions/). Это свойство не поддерживает присваивание объектов типа **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual void Aspose::Slides::Export::ISwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Класс [ISwfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)