---
title: Flatten()
second_title: Aspose.Slides for C++ API Reference
description: Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used.
type: docs
weight: 391
url: /cpp/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() method


Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) method


Flattens each curve in the path by converting them into a series of connected lines. The flatness value of 0.25 is used.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | The transform matrix to apply to the path before flattening |

## GraphicsPath::Flatten(const MatrixPtr\&, float) method


Flattens each curve in the path by converting them into a series of connected lines.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | The transform matrix to apply to the path before flattening |
| flatness | **float** | Specifies the maximum permitted error between the curve and its flattened approximation |

## See Also

* Typedef [MatrixPtr](../../matrixptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)