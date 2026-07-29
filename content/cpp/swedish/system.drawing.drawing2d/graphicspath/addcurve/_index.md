---
title: AddCurve()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet.
type: docs
weight: 274
url: /sv/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) metod

Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punkter som specificerar kurvan |
| tension | **float** | Anger hur mycket kurvan böjer sig mellan kontrollpunkterna |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) metod

Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punkter som specificerar kurvan |
| tension | **float** | Anger hur mycket kurvan böjer sig mellan kontrollpunkterna |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) metod

Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punkter som specificerar kurvan |
| offset | int | Indexet för punkten i **points** som används som startpunkt för kurvan |
| number_of_segments | int | Antalet segment som används för att rita kurvan |
| tension | **float** | Anger hur mycket kurvan böjer sig mellan kontrollpunkterna |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) metod

Lägger till den angivna kurvan till den bana som representeras av det aktuella objektet.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punkter som specificerar kurvan |
| offset | int | Indexet för punkten i **points** som används som startpunkt för kurvan |
| number_of_segments | int | Antalet segment som används för att rita kurvan |
| tension | **float** | Anger hur mycket kurvan böjer sig mellan kontrollpunkterna |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [PointF](../../../system.drawing/pointf/)
* Klass [GraphicsPath](../)
* Klass [Point](../../../system.drawing/point/)
* Namnrymd [System::Drawing::Drawing2D](../../)
* Bibliotek [Aspose.Slides](../../../)