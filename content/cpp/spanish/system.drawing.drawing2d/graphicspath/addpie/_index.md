---
title: AddPie()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual.
type: docs
weight: 209
url: /es/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) método

Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada X de la esquina superior izquierda del rectángulo que delimita la elipse de la cual se dibuja el pastel |
| y | **float** | La coordenada Y de la esquina superior izquierda del rectángulo que delimita la elipse de la cual se dibuja el pastel |
| width | **float** | El ancho del rectángulo que delimita la elipse de la cual se dibuja el pastel |
| height | **float** | La altura del rectángulo que delimita la elipse de la cual se dibuja el pastel |
| startAngle | **float** | Especifica el ángulo inicial del pastel en grados, medido en sentido horario desde el eje X |
| sweepAngle | **float** | Especifica el ángulo entre el ángulo inicial y el final del pastel |

## GraphicsPath::AddPie(int, int, int, int, float, float) método

Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada X de la esquina superior izquierda del rectángulo que delimita la elipse de la cual se dibuja el pastel |
| y | int | La coordenada Y de la esquina superior izquierda del rectángulo que delimita la elipse de la cual se dibuja el pastel |
| width | int | El ancho del rectángulo que delimita la elipse de la cual se dibuja el pastel |
| height | int | La altura del rectángulo que delimita la elipse de la cual se dibuja el pastel |
| startAngle | **float** | Especifica el ángulo inicial del pastel en grados, medido en sentido horario desde el eje X |
| sweepAngle | **float** | Especifica el ángulo entre el ángulo inicial y el final del pastel |

## GraphicsPath::AddPie(const Rectangle\&, float, float) método

Agrega el contorno especificado de la forma de pastel a la ruta representada por el objeto actual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | El rectángulo que delimita la elipse de la cual se dibuja el pastel |
| startAngle | **float** | Especifica el ángulo inicial del pastel en grados, medido en sentido horario desde el eje X |
| sweepAngle | **float** | Especifica el ángulo entre el ángulo inicial y el final del pastel |

## Ver también

* Clase [GraphicsPath](../)
* Clase [Rectangle](../../../system.drawing/rectangle/)
* Espacio de nombres [System::Drawing::Drawing2D](../../)
* Biblioteca [Aspose.Slides](../../../)