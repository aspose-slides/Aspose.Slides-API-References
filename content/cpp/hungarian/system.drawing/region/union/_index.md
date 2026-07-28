---
title: Union()
second_title: Aspose.Slides C++ API hivatkozás
description: Lecseréli a jelenlegi objektum által képviselt területet a jelen terület és a megadott téglalap által definiált terület uniójának eredményével.
type: docs
weight: 53
url: /hu/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) metódus

Lecseréli a jelenlegi objektum által képviselt területet a jelen terület és a megadott téglalap által definiált terület uniójának eredményével.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Egy téglalap, amely meghatározza a területet, amelyhez egyesíteni kell ezt a területet |

## Region::Union(const Rectangle\&) metódus

Lecseréli a jelenlegi objektum által képviselt területet a jelen terület és a megadott téglalap által definiált terület uniójának eredményével.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Egy téglalap, amely meghatározza a területet, amelyhez egyesíteni kell ezt a területet |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metódus

Lecseréli a jelenlegi objektum által képviselt területet a jelen terület és a megadott útvonal által definiált terület uniójának eredményével.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Egy útvonal, amely meghatározza a területet, amelyhez egyesíteni kell ezt a területet |

## Region::Union(const SharedPtr\<Region\>\&) metódus

Lecseréli a jelenlegi objektum által képviselt területet a jelen terület és a megadott terület uniójának eredményével.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Egy terület, amelyhez egyesíteni kell ezt a területet |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [RectangleF](../../rectanglef/)
* Osztály [Region](../)
* Osztály [Rectangle](../../rectangle/)
* Osztály [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Névtér [System::Drawing](../../)
* Library [Aspose.Slides](../../../)