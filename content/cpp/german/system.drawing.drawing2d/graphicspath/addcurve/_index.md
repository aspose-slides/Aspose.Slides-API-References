---
title: AddCurve()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt die angegebene Kurve zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.
type: docs
weight: 274
url: /de/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) Methode

Fügt die angegebene Kurve zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punkte, die die Kurve angeben |
| tension | **float** | Gibt die Stärke der Krümmung zwischen den Kontrollpunkten an |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) Methode

Fügt die angegebene Kurve zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punkte, die die Kurve angeben |
| tension | **float** | Gibt die Stärke der Krümmung zwischen den Kontrollpunkten an |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) Methode

Fügt die angegebene Kurve zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punkte, die die Kurve angeben |
| offset | int | Der Index des Punktes in **points**, der als Startpunkt der Kurve verwendet wird |
| number_of_segments | int | Die Anzahl der Segmente, die zum Zeichnen der Kurve verwendet werden |
| tension | **float** | Gibt die Stärke der Krümmung zwischen den Kontrollpunkten an |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) Methode

Fügt die angegebene Kurve zum Pfad hinzu, der durch das aktuelle Objekt dargestellt wird.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punkte, die die Kurve angeben |
| offset | int | Der Index des Punktes in **points**, der als Startpunkt der Kurve verwendet wird |
| number_of_segments | int | Die Anzahl der Segmente, die zum Zeichnen der Kurve verwendet werden |
| tension | **float** | Gibt die Stärke der Krümmung zwischen den Kontrollpunkten an |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [GraphicsPath](../)
* Klasse [Point](../../../system.drawing/point/)
* Namensraum [System::Drawing::Drawing2D](../../)
* Bibliothek [Aspose.Slides](../../../)