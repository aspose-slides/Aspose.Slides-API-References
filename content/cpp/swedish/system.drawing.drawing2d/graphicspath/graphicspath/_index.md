---
title: GraphicsPath()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av GraphicsPath-klassen med det angivna fyllningsläget.
type: docs
weight: 1
url: /sv/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) konstruktör


Skapar en ny instans av [GraphicsPath](../) klass med det angivna fyllningsläget.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Anger hur insidan av den slutna bana som representeras av det objekt som skapas ska fyllas |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) konstruktör


Skapar en ny instans av [GraphicsPath](../) objekt som representerar den angivna banan.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | En array som innehåller de punkter som specificerar banan som ska representeras av det objekt som skapas |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | En array som innehåller värdena som specificerar typerna för motsvarande punkter i **pts**-arrayen |
| fillMode | [FillMode](../../fillmode/) | Anger hur insidan av den slutna bana som representeras av det objekt som skapas ska fyllas |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) konstruktör


Skapar en ny instans av [GraphicsPath](../) objekt som representerar den angivna banan.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | En array som innehåller de punkter som specificerar banan som ska representeras av det objekt som skapas |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | En array som innehåller värdena som specificerar typerna för motsvarande punkter i **pts**-arrayen |
| fillMode | [FillMode](../../fillmode/) | Anger hur insidan av den slutna bana som representeras av det objekt som skapas ska fyllas |

## GraphicsPath::GraphicsPath(const SkPath\&) konstruktör




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Se även

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [GraphicsPath](../)
* Klass [Point](../../../system.drawing/point/)
* Klass [PointF](../../../system.drawing/pointf/)
* Namnrymd [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)