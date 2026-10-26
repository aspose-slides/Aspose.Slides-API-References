---
title: RectangleF()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine neue Instanz des RectangleF-Objekts, das ein Rechteck mit X- und Y-Koordinaten sowie Breite und Höhe von 0 darstellt.
type: docs
weight: 1
url: /de/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() Konstruktor

Konstruiert eine neue Instanz des [RectangleF](../)-Objekts, das ein Rechteck mit X- und Y-Koordinaten sowie Breite und Höhe von 0 darstellt.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) Konstruktor

Konstruiert eine neue Instanz des [RectangleF](../)-Objekts, das ein Rechteck mit den angegebenen Koordinaten seiner oberen linken Ecke sowie Breite und Höhe darstellt.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Der X-Koordinatenwert der oberen linken Ecke des Rechtecks |
| y | **float** | Der Y-Koordinatenwert der oberen linken Ecke des Rechtecks |
| width | **float** | Die Breite des Rechtecks |
| height | **float** | Die Höhe des Rechtecks |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) Konstruktor

Konstruiert eine neue Instanz des [RectangleF](../)-Objekts, das ein Rechteck mit den Koordinaten seiner oberen linken Ecke, angegeben als Instanz der [PointF](../../pointf/)-Klasse, sowie Breite und Höhe als Instanz der [SizeF](../../sizef/)-Klasse darstellt.

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Gibt die Position der oberen linken Ecke des Rechtecks an |
| size | const [SizeF](../../sizef/)\& | Gibt die Breite und Höhe des Rechtecks an |

## RectangleF::RectangleF(const Rectangle\&) Konstruktor

Konstruiert eine neue Instanz des [RectangleF](../)-Objekts, das das Rechteck darstellt, das dem angegebenen entspricht.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Eine Instanz der [Rectangle](../../rectangle/)-Klasse, die Position und Größe des Rechtecks angibt, das vom zu erstellenden Objekt repräsentiert wird |

## Siehe auch

* Klasse [RectangleF](../)
* Klasse [PointF](../../pointf/)
* Klasse [SizeF](../../sizef/)
* Klasse [Rectangle](../../rectangle/)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)