---
title: AddCurve()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá zadanou křivku do cesty reprezentované aktuálním objektem.
type: docs
weight: 274
url: /cs/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) metoda


Přidá zadanou křivku do cesty reprezentované aktuálním objektem.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Body, které určují křivku |
| tension | **float** | Určuje míru, jakou se křivka ohýbá mezi řídicími body |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) metoda


Přidá zadanou křivku do cesty reprezentované aktuálním objektem.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Body, které určují křivku |
| tension | **float** | Určuje míru, jakou se křivka ohýbá mezi řídicími body |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) metoda


Přidá zadanou křivku do cesty reprezentované aktuálním objektem.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Body, které určují křivku |
| offset | int | Index bodu v **points**, který je použit jako počáteční bod křivky |
| number_of_segments | int | Počet segmentů použitých k vykreslení křivky |
| tension | **float** | Určuje míru, jakou se křivka ohýbá mezi řídicími body |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) metoda


Přidá zadanou křivku do cesty reprezentované aktuálním objektem.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Body, které určují křivku |
| offset | int | Index bodu v **points**, který je použit jako počáteční bod křivky |
| number_of_segments | int | Počet segmentů použitých k vykreslení křivky |
| tension | **float** | Určuje míru, jakou se křivka ohýbá mezi řídicími body |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [PointF](../../../system.drawing/pointf/)
* Třída [GraphicsPath](../)
* Třída [Point](../../../system.drawing/point/)
* Jmenný prostor [System::Drawing::Drawing2D](../../)
* Knihovna [Aspose.Slides](../../../)