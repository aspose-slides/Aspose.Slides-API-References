---
title: Xor()
second_title: Aspose.Slides for C++ API-referencia
description: Lecseréli az aktuális objektum által képviselt regiont a jelenlegi region és a megadott téglalap által definiált region azon részeire, amelyek nem metszik egymást.
type: docs
weight: 144
url: /hu/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) metódus

Lecseréli az aktuális objektum által képviselt regiont a jelenlegi region és a megadott RectangleF által definiált region azon részeire, amelyek nem metszik egymást.

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Egy téglalap, amely meghatároz egy regiont a jelenlegi objektum által képviselt regionrel való xor művelethez |

## Region::Xor(const Rectangle\&) metódus

Lecseréli az aktuális objektum által képviselt regiont a jelenlegi region és a megadott Rectangle által definiált region azon részeire, amelyek nem metszik egymást.

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Egy téglalap, amely meghatároz egy regiont a jelenlegi objektum által képviselt regionrel való xor művelethez |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metódus

Lecseréli az aktuális objektum által képviselt regiont a jelenlegi region és a megadott GraphicsPath által definiált region azon részeire, amelyek nem metszik egymást.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Egy útvonal, amely meghatároz egy regiont a jelenlegi objektum által képviselt regionrel való xor művelethez |

## Region::Xor(const SharedPtr\<Region\>\&) metódus

Lecseréli az aktuális objektum által képviselt regiont a jelenlegi region és a megadott region azon részeire, amelyek nem metszik egymást.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Egy region, amely meghatároz egy regiont a jelenlegi objektum által képviselt regionrel való xor művelethez |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)