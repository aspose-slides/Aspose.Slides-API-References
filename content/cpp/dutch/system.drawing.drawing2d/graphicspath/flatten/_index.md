---
title: Flatten()
second_title: Aspose.Slides voor C++ API-referentie
description: Vlaagt elke curve in het pad af door ze om te zetten in een reeks verbonden lijnen. De vlakheidswaarde van 0.25 wordt gebruikt.
type: docs
weight: 391
url: /nl/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() methode

Vlaagt elke curve in het pad af door ze om te zetten in een reeks verbonden lijnen. De vlakheidswaarde van 0.25 wordt gebruikt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) methode

Vlaagt elke curve in het pad af door ze om te zetten in een reeks verbonden lijnen. De vlakheidswaarde van 0.25 wordt gebruikt.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | De transformatie-matrix die op het pad moet worden toegepast vóór het afvlakken |

## GraphicsPath::Flatten(const MatrixPtr\&, float) methode

Vlaagt elke curve in het pad af door ze om te zetten in een reeks verbonden lijnen.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | De transformatie-matrix die op het pad moet worden toegepast vóór het afvlakken |
| flatness | **float** | Specificeert de maximaal toegestane fout tussen de curve en de afgevlakte benadering |

## Zie ook

* Typedef [MatrixPtr](../../matrixptr/)
* Klasse [GraphicsPath](../)
* Naamruimte [System::Drawing::Drawing2D](../../)
* Bibliotheek [Aspose.Slides](../../../)