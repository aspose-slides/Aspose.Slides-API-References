---
title: SetClip()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает область отсечения поверхности рисования, представленной текущим объектом Graphics, в результат указанной операции, которая объединяет текущую область отсечения и указанную область.
type: docs
weight: 690
url: /ru/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) метод

Устанавливает область отсечения поверхности рисования, представленной текущим объектом [Graphics](../), в результат указанной операции, которая объединяет текущую область отсечения и указанную область.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Указывает область для объединения |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Указывает операцию объединения |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) метод

Устанавливает область отсечения поверхности рисования, представленной текущим объектом [Graphics](../), в результат указанной операции, которая объединяет текущую область отсечения и указанную область.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Указывает область для объединения |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Указывает операцию объединения |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) метод

Устанавливает область отсечения поверхности рисования, представленной текущим объектом [Graphics](../), в результат указанной операции, которая объединяет текущую область отсечения и указанную область.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Указывает область для объединения |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Указывает операцию объединения |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) метод

НЕ РЕАЛИЗОВАНО.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) метод

Устанавливает область отсечения поверхности рисования, представленной текущим объектом [Graphics](../), в результат указанной операции, которая объединяет текущую область отсечения и область, указанную графическим путем.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Указывает область для объединения |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Указывает операцию объединения |

## См. также

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Region](../../region/)
* Класс [Graphics](../)
* Класс [Rectangle](../../rectangle/)
* Класс [RectangleF](../../rectanglef/)
* Класс [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Пространство имён [System::Drawing](../../)
* Library [Aspose.Slides](../../../)