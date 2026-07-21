---
title: get_Description()
second_title: Aspose.Slides для справочника API C++
description: Возвращает текстовое описание объекта Summary Zoom Section.
type: docs
weight: 27
url: /ru/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() метод


Возвращает текстовое описание объекта Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
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
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)