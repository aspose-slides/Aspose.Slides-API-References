---
title: get_Title()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает текстовый заголовок объекта Summary Zoom Section.
type: docs
weight: 1
url: /ru/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() метод


Возвращает текстовый заголовок объекта Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
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
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)