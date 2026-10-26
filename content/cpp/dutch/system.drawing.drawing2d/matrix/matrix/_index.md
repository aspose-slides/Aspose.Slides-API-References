---
title: Matrix()
second_title: Aspose.Slides voor C++ API Referentie
description: Construeert een nieuw exemplaar van de Matrix-klasse die een identiteitsmatrix vertegenwoordigt.
type: docs
weight: 1
url: /nl/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() constructor

Construeert een nieuw exemplaar van de [Matrix](../) klasse die een identiteitsmatrix vertegenwoordigt.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) constructor

Construeert een nieuw exemplaar van de [Matrix](../) klasse en initialiseert deze met de opgegeven waarden.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m11 | **float** | De waarde van de 1e rij 1e kolom |
| m12 | **float** | De waarde van de 1e rij 2e kolom |
| m21 | **float** | De waarde van de 2e rij 1e kolom |
| m22 | **float** | De waarde van de 2e rij 2e kolom |
| dx | **float** | De waarde van de 3e rij 1e kolom |
| dy | **float** | De waarde van de 3e rij 2e kolom |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) constructor

Construeert een nieuw exemplaar van de [Matrix](../) klasse voor de geometrische transformatie die wordt gedefinieerd door de opgegeven rechthoek en array van punten.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) constructor

Construeert een nieuw exemplaar van de [Matrix](../) klasse voor de geometrische transformatie die wordt gedefinieerd door de opgegeven rechthoek en array van punten.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Matrix](../)
* Klasse [Rectangle](../../../system.drawing/rectangle/)
* Klasse [Point](../../../system.drawing/point/)
* Klasse [RectangleF](../../../system.drawing/rectanglef/)
* Klasse [PointF](../../../system.drawing/pointf/)
* namespace [System::Drawing::Drawing2D](../../)
* Bibliotheek [Aspose.Slides](../../../)