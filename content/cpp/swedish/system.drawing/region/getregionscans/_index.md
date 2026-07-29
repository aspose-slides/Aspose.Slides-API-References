---
title: GetRegionScans()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en array av RectangleF-strukturer som approximerar denna Region efter att den angivna matrisomvandlingen har tillämpats.
type: docs
weight: 27
url: /sv/system.drawing/region/getregionscans/
---
## Region::GetRegionScans(const SharedPtr\<Drawing2D::Matrix\>\&) const metod


Returnerar en array av [RectangleF](../../rectanglef/) strukturer som approximerar denna [Region](../) efter att den angivna matrisomvandlingen har tillämpats.

```cpp
ArrayPtr<RectangleF> System::Drawing::Region::GetRegionScans(const SharedPtr<Drawing2D::Matrix> &matrix) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | En Matrix som representerar en geometrisk transformation att tillämpa på regionen. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [RectangleF](../../rectanglef/)
* Klass [Matrix](../../../system.drawing.drawing2d/matrix/)
* Klass [Region](../)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)