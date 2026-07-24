---
title: Exclude()
second_title: Aspose.Slides für C++ API Referenz
description: Ersetzt die durch das aktuelle Objekt dargestellte Region durch das Ergebnis der Ausschließung der durch das angegebene Rechteck definierten Region.
type: docs
weight: 92
url: /de/system.drawing/region/exclude/
---
## Region::Exclude(const RectangleF\&) Methode

Ersetzt die durch das aktuelle Objekt dargestellte Region durch das Ergebnis der Ausschließung der durch das angegebene Rechteck definierten Region.

```cpp
void System::Drawing::Region::Exclude(const RectangleF &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Ein Rechteck, das eine auszuschließende Region definiert. |

## Region::Exclude(const Rectangle\&) Methode

Ersetzt die durch das aktuelle Objekt dargestellte Region durch das Ergebnis der Ausschließung der durch das angegebene Rechteck definierten Region.

```cpp
void System::Drawing::Region::Exclude(const Rectangle &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Ein Rechteck, das eine auszuschließende Region definiert. |

## Region::Exclude(const SharedPtr\<Drawing2D::GraphicsPath\>\&) Methode

Ersetzt die durch das aktuelle Objekt dargestellte Region durch das Ergebnis der Ausschließung der durch den angegebenen Pfad definierten Region.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Ein Pfad, der eine auszuschließende Region definiert. |

## Region::Exclude(const SharedPtr\<Region\>\&) Methode

Ersetzt die durch das aktuelle Objekt dargestellte Region durch das Ergebnis der Ausschließung der angegebenen Region.

```cpp
void System::Drawing::Region::Exclude(const SharedPtr<Region> &region)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Eine auszuschließende Region. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [Region](../)
* Klasse [Rectangle](../../rectangle/)
* Klasse [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)