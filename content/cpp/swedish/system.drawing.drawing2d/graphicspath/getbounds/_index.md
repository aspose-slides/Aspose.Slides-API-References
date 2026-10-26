---
title: GetBounds()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett RectangleF-objekt som representerar en rektangel som omsluter den sökväg som representeras av det aktuella objektet när det transformeras med den angivna matrisen.
type: docs
weight: 339
url: /sv/system.drawing.drawing2d/graphicspath/getbounds/
---
## GraphicsPath::GetBounds(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const metod

Returnerar ett [RectangleF](../../../system.drawing/rectanglef/) objekt som representerar en rektangel som omsluter sökvägen som representeras av det aktuella objektet när det transformeras med den specificerade matrisen.

```cpp
RectangleF System::Drawing::Drawing2D::GraphicsPath::GetBounds(const MatrixPtr &matrix=nullptr, const SharedPtr<Pen> &pen=nullptr) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Transformationsmatrisen |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../../system.drawing/pen/)\>\& | En [Pen](../../../system.drawing/pen/) för att beräkna den omgivande rektangeln. |

## Se även

* Typedef [MatrixPtr](../../matrixptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [Pen](../../../system.drawing/pen/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)