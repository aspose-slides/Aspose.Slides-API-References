---
title: GetBounds()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt ein RectangleF-Objekt zurück, das ein Rechteck darstellt, das den Pfad begrenzt, der vom aktuellen Objekt dargestellt wird, wenn es mit der angegebenen Matrix transformiert wird.
type: docs
weight: 339
url: /de/system.drawing.drawing2d/graphicspath/getbounds/
---
## GraphicsPath::GetBounds(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const Methode

Gibt ein [RectangleF](../../../system.drawing/rectanglef/)-Objekt zurück, das ein Rechteck darstellt, das den Pfad begrenzt, der vom aktuellen Objekt dargestellt wird, wenn er mit der angegebenen Matrix transformiert wird.

```cpp
RectangleF System::Drawing::Drawing2D::GraphicsPath::GetBounds(const MatrixPtr &matrix=nullptr, const SharedPtr<Pen> &pen=nullptr) const
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Die Transformationsmatrix |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../../system.drawing/pen/)\>\& | Ein [Pen](../../../system.drawing/pen/) zum Berechnen des umgebenden Rechtecks. |

## Siehe auch

* Typedef [MatrixPtr](../../matrixptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RectangleF](../../../system.drawing/rectanglef/)
* Klasse [Pen](../../../system.drawing/pen/)
* Klasse [GraphicsPath](../)
* Namensraum [System::Drawing::Drawing2D](../../)
* Bibliothek [Aspose.Slides](../../../)