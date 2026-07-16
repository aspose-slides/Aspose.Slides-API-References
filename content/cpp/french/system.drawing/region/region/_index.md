---
title: Region()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance de la classe Region.
type: docs
weight: 1
url: /fr/system.drawing/region/region/
---
## Region::Region() constructeur

Construit une nouvelle instance de la classe [Region](../).

```cpp
System::Drawing::Region::Region()
```

## Region::Region(const RectangleF\&) constructeur

Construit une nouvelle instance de la classe [Region](../) qui représente une région définie par le rectangle spécifié.

```cpp
System::Drawing::Region::Region(const RectangleF &rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Un rectangle qui définit la région |

## Region::Region(const Rectangle\&) constructeur

Construit une nouvelle instance de la classe [Region](../) qui représente une région définie par le rectangle spécifié.

```cpp
System::Drawing::Region::Region(const Rectangle &rect)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Un rectangle qui définit la région |

## Region::Region(const SharedPtr\<Drawing2D::GraphicsPath\>\&) constructeur

Construit une nouvelle instance de la classe [Region](../) qui représente une région définie par le chemin spécifié.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Un chemin qui définit la région |

## Region::Region(const SkPath\&) constructeur

```cpp
System::Drawing::Region::Region(const SkPath &path)
```

## Region::Region(const SharedPtr\<Drawing2D::RegionData\>\&) constructeur

Construit une nouvelle instance de la classe [Region](../) qui représente une région définie par l'objet RegionData spécifié.

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::RegionData> &region_data)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| region_data | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::RegionData](../../../system.drawing.drawing2d/regiondata/)\>\& | Un objet RegionData qui définit la région |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Class [RegionData](../../../system.drawing.drawing2d/regiondata/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)