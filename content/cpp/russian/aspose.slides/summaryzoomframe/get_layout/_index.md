---
title: get_Layout()
second_title: Aspose.Slides для C++ справочник API
description: Получает компоновку разделов Summary Zoom в кадре. Значение по умолчанию — GridLayout.
type: docs
weight: 1
url: /ru/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() метод

Получает компоновку разделов Summary Zoom в кадре. Значение по умолчанию — GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Примечания

Пример демонстрирует получение элемента Summary Zoom [Section](../../section/) по индексу:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Смотрите также

* Перечисление [ZoomLayout](../../zoomlayout/)
* Класс [SummaryZoomFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)