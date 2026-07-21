---
title: set_Description()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает текстовое описание объекта Summary Zoom Section.
type: docs
weight: 40
url: /ru/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) метод


Возвращает текстовое описание объекта Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
```

## Примечания


Пример:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## См. также

* Класс [String](../../../system/string/)
* Класс [ISummaryZoomSection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)