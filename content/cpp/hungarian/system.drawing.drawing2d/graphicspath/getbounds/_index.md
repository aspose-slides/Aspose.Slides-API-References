---
title: GetBounds()
second_title: Aspose.Slides C++ API referenciája
description: Visszaad egy RectangleF objektumot, amely egy téglalapot ábrázol, amely körülhatárolja az aktuális objektum által képviselt útvonalat, amikor azt a megadott mátrixszal transzformálják.
type: docs
weight: 339
url: /hu/system.drawing.drawing2d/graphicspath/getbounds/
---
## GraphicsPath::GetBounds(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const metódus

Visszaad egy [RectangleF](../../../system.drawing/rectanglef/) objektumot, amely egy téglalapot ábrázol, amely körülhatárolja az aktuális objektum által képviselt útvonalat, amikor azt a megadott mátrixszal transzformálják.

```cpp
RectangleF System::Drawing::Drawing2D::GraphicsPath::GetBounds(const MatrixPtr &matrix=nullptr, const SharedPtr<Pen> &pen=nullptr) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | A transzformációs mátrix |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../../system.drawing/pen/)\>\& | Egy [Pen](../../../system.drawing/pen/) a körülhatároló téglalap kiszámításához. |

## Lásd még

* Típusdefiníció [MatrixPtr](../../matrixptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [RectangleF](../../../system.drawing/rectanglef/)
* Osztály [Pen](../../../system.drawing/pen/)
* Osztály [GraphicsPath](../)
* Névtér [System::Drawing::Drawing2D](../../)
* Könyvtár [Aspose.Slides](../../../)