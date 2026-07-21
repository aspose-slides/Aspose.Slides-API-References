---
title: get_SlidesLayoutOptions()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает режим, в котором слайды размещаются на странице при экспорте презентации ISlidesLayoutOptions. Это свойство не поддерживает назначение объектов типа Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 391
url: /ru/aspose.slides.export/iswfoptions/get_slideslayoutoptions/
---
## ISwfOptions::get_SlidesLayoutOptions() метод


Получает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../islideslayoutoptions/). Это свойство не поддерживает назначение объектов типа **[Aspose.Slides.Export.HandoutLayoutingOptions](../../handoutlayoutingoptions/)**

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ISwfOptions::get_SlidesLayoutOptions()=0
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

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Класс [ISwfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)