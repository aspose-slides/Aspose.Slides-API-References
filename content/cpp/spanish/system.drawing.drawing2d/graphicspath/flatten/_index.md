---
title: Flatten()
second_title: Referencia de API de Aspose.Slides para C++
description: Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas. Se usa el valor de planitud de 0.25.
type: docs
weight: 391
url: /es/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() método

Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas. Se usa el valor de planitud de 0.25.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) método

Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas. Se usa el valor de planitud de 0.25.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | La matriz de transformación a aplicar a la ruta antes de aplanar |

## GraphicsPath::Flatten(const MatrixPtr\&, float) método

Aplana cada curva en la ruta convirtiéndolas en una serie de líneas conectadas.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | La matriz de transformación a aplicar a la ruta antes de aplanar |
| flatness | **float** | Especifica el error máximo permitido entre la curva y su aproximación aplanada |

## Véase también

* Typedef [MatrixPtr](../../matrixptr/)
* Clase [GraphicsPath](../)
* Espacio de nombres [System::Drawing::Drawing2D](../../)
* Biblioteca [Aspose.Slides](../../../)