---
title: Intersect()
second_title: Aspose.Slides for C++ API referenciája
description: A jelenlegi objektum által képviselt régiót lecseréli a jelenlegi régió és a megadott téglalap által meghatározott régió metszetének eredményére.
type: docs
weight: 79
url: /hu/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) metódus

Lecseréli a jelenlegi objektum által képviselt régiót azzal az eredménnyel, amely e régió és az adott téglalap által meghatározott régió metszete.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Egy téglalap, amely meghatároz egy olyan régiót, amellyel ezt a régiót metszik |

## Region::Intersect(const Rectangle\&) metódus

Lecseréli a jelenlegi objektum által képviselt régiót azzal az eredménnyel, amely e régió és az adott téglalap által meghatározott régió metszete.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Egy téglalap, amely meghatároz egy olyan régiót, amellyel ezt a régiót metszik |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metódus

Lecseréli a jelenlegi objektum által képviselt régiót azzal az eredménnyel, amely e régió és az adott útvonal által meghatározott régió metszete.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Egy útvonal, amely meghatároz egy olyan régiót, amellyel ezt a régiót metszik |

## Region::Intersect(const SharedPtr\<Region\>\&) metódus

Lecseréli a jelenlegi objektum által képviselt régiót azzal az eredménnyel, amely e régió és a megadott régió metszete.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Egy régió, amelyet ezzel a régióval metszik |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [RectangleF](../../rectanglef/)
* Osztály [Region](../)
* Osztály [Rectangle](../../rectangle/)
* Osztály [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Névtér [System::Drawing](../../)
* Library [Aspose.Slides](../../../)