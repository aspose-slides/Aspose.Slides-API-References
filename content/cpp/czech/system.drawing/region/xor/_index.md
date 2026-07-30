---
title: Xor()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Nahrazuje oblast reprezentovanou aktuálním objektem částmi této oblasti a oblastí definované zadaným obdélníkem, které se nepřekrývají.
type: docs
weight: 144
url: /cs/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) method

Nahrazuje oblast reprezentovanou aktuálním objektem částmi této oblasti a oblastí definované zadaným obdélníkem, které se nepřekrývají.

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Obdélník, který definuje oblast, se kterou se má provést operace xor s oblastí reprezentovanou aktuálním objektem |

## Region::Xor(const Rectangle\&) method

Nahrazuje oblast reprezentovanou aktuálním objektem částmi této oblasti a oblastí definované zadaným obdélníkem, které se nepřekrývají.

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, který definuje oblast, se kterou se má provést operace xor s oblastí reprezentovanou aktuálním objektem |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) method

Nahrazuje oblast reprezentovanou aktuálním objektem částmi této oblasti a oblastí definované zadanou cestou, které se nepřekrývají.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Cesta, která definuje oblast, se kterou se má provést operace xor s oblastí reprezentovanou aktuálním objektem |

## Region::Xor(const SharedPtr\<Region\>\&) method

Nahrazuje oblast reprezentovanou aktuálním objektem částmi této oblasti a zadanou oblastí, které se nepřekrývají.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Oblast, se kterou se má provést operace xor s oblastí reprezentovanou aktuálním objektem |

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [RectangleF](../../rectanglef/)
* Třída [Region](../)
* Třída [Rectangle](../../rectangle/)
* Třída [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)