---
title: DrawClosedCurve()
second_title: Справочник API Aspose.Slides для C++ 
description: Рисует замкнутый сплайн, используя указанное перо.
type: docs
weight: 781
url: /ru/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) метод

Рисует замкнутый сплайн, используя указанное перо.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании сплайна |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| tension | **float** | Значение, определяющее натяжение сплайна |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | ИГНОРИРУЕТСЯ |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) метод

Рисует замкнутый сплайн, используя указанное перо.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Перо, используемое при рисовании сплайна |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) точек, определяющих сплайн |
| tension | **float** | Значение, определяющее натяжение сплайна |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | ИГНОРИРУЕТСЯ |

## См. также

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Pen](../../pen/)
* Класс [Point](../../point/)
* Класс [Graphics](../)
* Класс [PointF](../../pointf/)
* Пространство имён [System::Drawing](../../)
* Library [Aspose.Slides](../../../)