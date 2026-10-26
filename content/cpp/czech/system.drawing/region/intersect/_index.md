---
title: Intersect()
second_title: Aspose.Slides pro C++ API Reference
description: Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem průniku této oblasti a oblastí definované zadaným obdélníkem.
type: docs
weight: 79
url: /cs/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) metoda

Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem průniku této oblasti a oblasti definované zadaným obdélníkem.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Obdélník, který definuje oblast, se kterou se má tato oblast překřížit |

## Region::Intersect(const Rectangle\&) metoda

Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem průniku této oblasti a oblasti definované zadaným obdélníkem.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, který definuje oblast, se kterou se má tato oblast překřížit |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metoda

Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem průniku této oblasti a oblasti definované zadanou cestou.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Cesta, která definuje oblast, se kterou se má tato oblast překřížit |

## Region::Intersect(const SharedPtr\<Region\>\&) metoda

Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem průniku této oblasti a zadané oblasti.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Oblast, se kterou se má tato oblast překřížit |

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [RectangleF](../../rectanglef/)
* Třída [Region](../)
* Třída [Rectangle](../../rectangle/)
* Třída [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)