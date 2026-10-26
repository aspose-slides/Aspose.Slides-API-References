---
title: Region()
second_title: Aspose.Slides pro C++ referenci API
description: Vytvoří novou instanci třídy Region.
type: docs
weight: 1
url: /cs/system.drawing/region/region/
---
## Region::Region() konstruktor


Vytvoří novou instanci třídy [Region](../).

```cpp
System::Drawing::Region::Region()
```

## Region::Region(const RectangleF\&) konstruktor


Vytvoří novou instanci třídy [Region](../), která představuje oblast definovanou zadaným obdélníkem.

```cpp
System::Drawing::Region::Region(const RectangleF &rect)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Obdélník, který určuje oblast |

## Region::Region(const Rectangle\&) konstruktor


Vytvoří novou instanci třídy [Region](../), která představuje oblast definovanou zadaným obdélníkem.

```cpp
System::Drawing::Region::Region(const Rectangle &rect)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Obdélník, který určuje oblast |

## Region::Region(const SharedPtr\<Drawing2D::GraphicsPath\>\&) konstruktor


Vytvoří novou instanci třídy [Region](../), která představuje oblast definovanou zadanou cestou.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::GraphicsPath> &path)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Cesta, která určuje oblast |

## Region::Region(const SkPath\&) konstruktor




```cpp
System::Drawing::Region::Region(const SkPath &path)
```

## Region::Region(const SharedPtr\<Drawing2D::RegionData\>\&) konstruktor


Vytvoří novou instanci třídy [Region](../), která představuje oblast definovanou zadaným objektem RegionData.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::RegionData> &region_data)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| region_data | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::RegionData](../../../system.drawing.drawing2d/regiondata/)\>\& | Objekt RegionData, který určuje oblast |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Class [RegionData](../../../system.drawing.drawing2d/regiondata/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)