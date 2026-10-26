---
title: set_Title()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает текстовый заголовок объекта Summary Zoom Section.
type: docs
weight: 14
url: /ru/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) метод

Возвращает текстовый заголовок объекта Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
```

## Примечания

Пример: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [ISummaryZoomSection](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)