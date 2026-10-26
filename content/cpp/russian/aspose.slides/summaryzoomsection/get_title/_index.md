---
title: get_Title()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает текстовое название объекта Summary Zoom Section.
type: docs
weight: 1
url: /ru/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() метод

Возвращает текстовое название объекта Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
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
* Класс [SummaryZoomSection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)