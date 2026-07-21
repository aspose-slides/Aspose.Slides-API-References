---
title: CustomLineCap()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый экземпляр класса CustomLineCap, который представляет пользовательскую головку линии с указанными свойствами.
type: docs
weight: 1
url: /ru/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) конструктор

Создаёт новый экземпляр класса [CustomLineCap](../), который представляет пользовательскую головку линии с указанными свойствами.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Указывает заливку пользовательской головки |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Указывает контур пользовательской головки |
| baseCap | [LineCap](../../linecap/) | Базовая головка линии, из которой создаётся пользовательская головка |
| baseInset | **float** | Указывает расстояние между линией и головкой |

## Смотрите также

* Перечисление [LineCap](../../linecap/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [GraphicsPath](../../graphicspath/)
* Класс [CustomLineCap](../)
* Пространство имён [System::Drawing::Drawing2D](../../)
* Библиотека [Aspose.Slides](../../../)