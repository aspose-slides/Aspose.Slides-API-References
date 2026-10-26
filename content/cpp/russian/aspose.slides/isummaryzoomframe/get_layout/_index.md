---
title: get_Layout()
second_title: Aspose.Slides для C++ — справочник API
description: Получает расположение разделов Summary Zoom в кадре. Значение по умолчанию — GridLayout.
type: docs
weight: 1
url: /ru/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() метод


Получает расположение разделов Summary Zoom в кадре. Значение по умолчанию — GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Примечания


Пример демонстрирует получение элемента Summary Zoom [Section](../../section/) по индексу: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## См. также

* Enum [ZoomLayout](../../zoomlayout/)
* Класс [ISummaryZoomFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)