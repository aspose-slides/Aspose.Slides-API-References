---
title: Union()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersetzt die von dem aktuellen Objekt dargestellte Region durch das Ergebnis der Vereinigungsoperation dieser Region und einer durch das angegebene Rechteck definierten Region.
type: docs
weight: 53
url: /de/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) Methode

Ersetzt die von dem aktuellen Objekt dargestellte Region durch das Ergebnis der Vereinigungsoperation dieser Region und einer durch das angegebene Rechteck definierten Region.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Ein Rechteck, das eine Region definiert, mit der diese Region vereinigt wird. |

## Region::Union(const Rectangle\&) Methode

Ersetzt die von dem aktuellen Objekt dargestellte Region durch das Ergebnis der Vereinigung dieser Region und einer durch das angegebene Rechteck definierten Region.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Ein Rechteck, das eine Region definiert, mit der diese Region vereinigt wird. |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) Methode

Ersetzt die von dem aktuellen Objekt dargestellte Region durch das Ergebnis der Vereinigung dieser Region und einer durch den angegebenen Pfad definierten Region.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Ein Pfad, der eine Region definiert, mit der diese Region vereinigt wird. |

## Region::Union(const SharedPtr\<Region\>\&) Methode

Ersetzt die von dem aktuellen Objekt dargestellte Region durch das Ergebnis der Vereinigung dieser Region und der angegebenen Region.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Eine Region, mit der diese Region vereinigt wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [Region](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)