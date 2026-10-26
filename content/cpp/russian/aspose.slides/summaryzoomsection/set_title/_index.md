---
title: set_Title()
second_title: Aspose.Slides для справочника API C++
description: Возвращает текстовый заголовок объекта Summary Zoom Section.
type: docs
weight: 14
url: /ru/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) метод


Возвращает текстовый заголовок объекта Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
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

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [SummaryZoomSection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)