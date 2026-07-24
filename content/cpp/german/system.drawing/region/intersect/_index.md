---
title: Intersect()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt die Region, die durch das aktuelle Objekt dargestellt wird, durch das Ergebnis der Schnittmenge dieser Region und einer Region, die durch das angegebene Rechteck definiert ist.
type: docs
weight: 79
url: /de/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) Methode

Ersetzt die Region, die durch das aktuelle Objekt dargestellt wird, durch das Ergebnis der Schnittmenge dieser Region und einer Region, die durch das angegebene Rechteck definiert ist.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Ein Rechteck, das eine Region definiert, mit der diese Region geschnitten wird |

## Region::Intersect(const Rectangle\&) Methode

Ersetzt die Region, die durch das aktuelle Objekt dargestellt wird, durch das Ergebnis der Schnittmenge dieser Region und einer Region, die durch das angegebene Rechteck definiert ist.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Ein Rechteck, das eine Region definiert, mit der diese Region geschnitten wird |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) Methode

Ersetzt die Region, die durch das aktuelle Objekt dargestellt wird, durch das Ergebnis der Schnittmenge dieser Region und einer Region, die durch den angegebenen Pfad definiert ist.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Ein Pfad, der eine Region definiert, mit der diese Region geschnitten wird |

## Region::Intersect(const SharedPtr\<Region\>\&) Methode

Ersetzt die Region, die durch das aktuelle Objekt dargestellt wird, durch das Ergebnis der Schnittmenge dieser Region und der angegebenen Region.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Eine Region, die mit dieser Region geschnitten wird |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [Region](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)