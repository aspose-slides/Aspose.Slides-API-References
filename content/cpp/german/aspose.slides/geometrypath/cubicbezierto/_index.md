---
title: CubicBezierTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt dem Pfad am Ende eine kubische Bézier-Kurve hinzu
type: docs
weight: 105
url: /de/aspose.slides/geometrypath/cubicbezierto/
---
## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) Methode

Fügt dem Pfad am Ende eine kubische Bézier-Kurve hinzu

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Erster Richtungs-Punkt |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Zweiter Richtungs-Punkt |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Endpunkt |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float) Methode

Fügt dem Pfad am Ende eine kubische Bézier-Kurve hinzu

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | **float** | X-Koordinate des ersten Richtungs-Punktes |
| y1 | **float** | Y-Koordinate des ersten Richtungs-Punktes |
| x2 | **float** | X-Koordinate des zweiten Richtungs-Punktes |
| y2 | **float** | Y-Koordinate des zweiten Richtungs-Punktes |
| x3 | **float** | X-Koordinate des Endpunkts |
| y3 | **float** | Y-Koordinate des Endpunkts |

## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) Methode

Fügt dem Pfad an der angegebenen Stelle eine kubische Bézier-Kurve hinzu

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Erster Richtungs-Punkt |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Zweiter Richtungs-Punkt |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Endpunkt |
| index | **uint32_t** | Index des Segments in PathData |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) Methode

Fügt dem Pfad an der angegebenen Stelle eine kubische Bézier-Kurve hinzu

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | **float** | X-Koordinate des ersten Richtungs-Punktes |
| y1 | **float** | Y-Koordinate des ersten Richtungs-Punktes |
| x2 | **float** | X-Koordinate des zweiten Richtungs-Punktes |
| y2 | **float** | Y-Koordinate des zweiten Richtungs-Punktes |
| x3 | **float** | X-Koordinate des Endpunkts |
| y3 | **float** | Y-Koordinate des Endpunkts |
| index | **uint32_t** | Index des Segments in PathData |

## Siehe auch

* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [GeometryPath](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)