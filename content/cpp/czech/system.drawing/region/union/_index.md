---
title: Union()
second_title: Aspose.Slides pro C++ – reference API
description: Nahrazuje oblast reprezentovanou aktuálním objektem výsledkem operace sjednocení této oblasti a oblasti definované zadaným obdélníkem.
type: docs
weight: 53
url: /cs/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) metoda

Nahradí oblast reprezentovanou aktuálním objektem výsledkem operace sjednocení této oblasti a oblasti definované zadaným obdélníkem.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Obdélník, který definuje oblast ke sjednocení s touto oblastí |

## Region::Union(const Rectangle\&) metoda

Nahradí oblast reprezentovanou aktuálním objektem výsledkem sjednocení této oblasti a oblasti definované zadaným obdélníkem.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, který definuje oblast ke sjednocení s touto oblastí |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metoda

Nahradí oblast reprezentovanou aktuálním objektem výsledkem sjednocení této oblasti a oblasti definované zadanou cestou.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Cesta, která definuje oblast ke sjednocení s touto oblastí |

## Region::Union(const SharedPtr\<Region\>\&) metoda

Nahradí oblast reprezentovanou aktuálním objektem výsledkem sjednocení této oblasti a zadané oblasti.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Oblast, se kterou se má tato oblast sjednotit |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [RectangleF](../../rectanglef/)
* Třída [Region](../)
* Třída [Rectangle](../../rectangle/)
* Třída [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Jmenný prostor [System::Drawing](../../)
* Library [Aspose.Slides](../../../)