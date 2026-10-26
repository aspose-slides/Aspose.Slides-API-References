---
title: AddCurve()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt de opgegeven curve toe aan het pad dat wordt weergegeven door het huidige object.
type: docs
weight: 274
url: /nl/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) methode


Voegt de opgegeven curve toe aan het pad dat wordt vertegenwoordigd door het huidige object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punten die de curve specificeren |
| tension | **float** | Specificeert de hoeveelheid waarmee de curve buigt tussen de controlepunten |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) methode


Voegt de opgegeven curve toe aan het pad dat wordt vertegenwoordigd door het huidige object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punten die de curve specificeren |
| tension | **float** | Specificeert de hoeveelheid waarmee de curve buigt tussen de controlepunten |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) methode


Voegt de opgegeven curve toe aan het pad dat wordt vertegenwoordigd door het huidige object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punten die de curve specificeren |
| offset | int | De index van het punt in **points** dat wordt gebruikt als het startpunt van de curve |
| number_of_segments | int | Het aantal segmenten dat wordt gebruikt om de curve te tekenen |
| tension | **float** | Specificeert de hoeveelheid waarmee de curve buigt tussen de controlepunten |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) methode


Voegt de opgegeven curve toe aan het pad dat wordt vertegenwoordigd door het huidige object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punten die de curve specificeren |
| offset | int | De index van het punt in **points** dat wordt gebruikt als het startpunt van de curve |
| number_of_segments | int | Het aantal segmenten dat wordt gebruikt om de curve te tekenen |
| tension | **float** | Specificeert de hoeveelheid waarmee de curve buigt tussen de controlepunten |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [GraphicsPath](../)
* Klasse [Point](../../../system.drawing/point/)
* Naamruimte [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)