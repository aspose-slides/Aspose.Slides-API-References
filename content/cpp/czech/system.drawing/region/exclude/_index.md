---
title: Exclude()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nahradí oblast reprezentovanou aktuálním objektem výsledkem vyloučení oblasti definované zadaným obdélníkem.
type: docs
weight: 92
url: /cs/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) metoda

Nahradí oblast reprezentovanou aktuálním objektem výsledkem vyloučení oblasti definované zadaným obdélníkem.

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Obdélník, který určuje oblast k vyloučení |

## Region::Exclude(const Rectangle\&) metoda

Nahradí oblast reprezentovanou aktuálním objektem výsledkem vyloučení oblasti definované zadaným obdélníkem.

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, který určuje oblast k vyloučení |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metoda

Nahradí oblast reprezentovanou aktuálním objektem výsledkem vyloučení oblasti definované zadanou cestou.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Cesta, která určuje oblast k vyloučení |

## Region::Exclude(const SharedPtr\<Region\>\&) metoda

Nahradí oblast reprezentovanou aktuálním objektem výsledkem vyloučení zadané oblasti.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Oblast k vyloučení |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RectangleF](../../rectanglef/)
* Třída [Region](../)
* Třída [Rectangle](../../rectangle/)
* Třída [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Jmenný prostor [System::Drawing](../../)
* Library [Aspose.Slides](../../../)