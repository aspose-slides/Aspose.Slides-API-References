---
title: Complement()
second_title: Aspose.Slides for C++ API-referencia
description: Az aktuális objektum által képviselt régiót a megadott téglalap által definiált régió azon részével cseréli ki, amely nem metszi ezt a régiót.
type: docs
weight: 131
url: /hu/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) metódus

A jelenlegi objektum által képviselt régiót kicseréli a megadott téglalap által meghatározott régió azon részével, amely nem metszi ezt a régiót.

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Egy téglalap, amely meghatároz egy kiegészítendő régiót |

## Region::Complement(const Rectangle\&) metódus

A jelenlegi objektum által képviselt régiót kicseréli a megadott téglalap által meghatározott régió azon részével, amely nem metszi ezt a régiót.

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Egy téglalap, amely meghatároz egy kiegészítendő régiót |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metódus

A jelenlegi objektum által képviselt régiót kicseréli a megadott út által meghatározott régió azon részével, amely nem metszi ezt a régiót.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Egy út, amely meghatároz egy kiegészítendő régiót |

## Region::Complement(const SharedPtr\<Region\>\&) metódus

A jelenlegi objektum által képviselt régiót kicseréli a megadott régió azon részével, amely nem metszi ezt a régiót.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Egy régió, amelyet kiegészítenek |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [RectangleF](../../rectanglef/)
* Osztály [Region](../)
* Osztály [Rectangle](../../rectangle/)
* Osztály [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)