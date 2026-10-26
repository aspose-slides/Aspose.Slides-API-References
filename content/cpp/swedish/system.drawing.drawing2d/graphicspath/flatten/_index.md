---
title: Flatten()
second_title: Aspose.Slides för C++ API-referens
description: Plattar ut varje kurva i vägen genom att konvertera dem till en serie av sammanhängande linjer. Flathetsvärdet 0.25 används.
type: docs
weight: 391
url: /sv/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() metod


Plattar ut varje kurva i vägen genom att konvertera dem till en serie av sammanhängande linjer. Flathetsvärdet 0.25 används.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) metod


Plattar ut varje kurva i vägen genom att konvertera dem till en serie av sammanhängande linjer. Flathetsvärdet 0.25 används.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Transformationsmatrisen som ska tillämpas på vägen innan plattning |

## GraphicsPath::Flatten(const MatrixPtr\&, float) metod


Plattar ut varje kurva i vägen genom att konvertera dem till en serie av sammanhängande linjer.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Transformationsmatrisen som ska tillämpas på vägen innan plattning |
| flatness | **float** | Anger det maximalt tillåtna felet mellan kurvan och dess plattade approximation |

## Se även

* Typdef [MatrixPtr](../../matrixptr/)
* Klass [GraphicsPath](../)
* Namnrymd [System::Drawing::Drawing2D](../../)
* Bibliotek [Aspose.Slides](../../../)