---
title: DrawPie()
second_title: Referencia de la API de Aspose.Slides para C++
description: Dibuja el sector especificado usando la pluma especificada en la superficie representada por el objeto actual.
type: docs
weight: 261
url: /es/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) método

Dibuja el sector especificado usando la pluma especificada en la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una pluma para usar al dibujar el sector |
| x | **int32_t** | La coordenada X de la esquina superior izquierda del rectángulo que define la elipse |
| y | **int32_t** | La coordenada Y de la esquina superior izquierda del rectángulo que define la elipse |
| width | **int32_t** | El ancho del rectángulo que define la elipse |
| height | **int32_t** | La altura del rectángulo que define la elipse |
| startAngle | **int32_t** | Ángulo en grados medido en sentido horario desde el eje X hasta el punto inicial del sector |
| sweepAngle | **int32_t** | Ángulo en grados medido en sentido horario desde el **startAngle** hasta el punto final del sector |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) método

Dibuja el sector especificado usando la pluma especificada en la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una pluma para usar al dibujar el sector |
| x | **float** | La coordenada X de la esquina superior izquierda del rectángulo que define la elipse |
| y | **float** | La coordenada Y de la esquina superior izquierda del rectángulo que define la elipse |
| width | **float** | El ancho del rectángulo que define la elipse |
| height | **float** | La altura del rectángulo que define la elipse |
| startAngle | **float** | Ángulo en grados medido en sentido horario desde el eje X hasta el punto inicial del sector |
| sweepAngle | **float** | Ángulo en grados medido en sentido horario desde el **startAngle** hasta el punto final del sector |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) método

Dibuja el sector especificado usando la pluma especificada en la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una pluma para usar al dibujar el sector |
| rect | [Rectangle](../../rectangle/) | El rectángulo que define la elipse |
| startAngle | **float** | Ángulo en grados medido en sentido horario desde el eje X hasta el punto inicial del sector |
| sweepAngle | **float** | Ángulo en grados medido en sentido horario desde el **startAngle** hasta el punto final del sector |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) método

Dibuja el sector especificado usando la pluma especificada en la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una pluma para usar al dibujar el sector |
| rect | [RectangleF](../../rectanglef/) | El rectángulo que define la elipse |
| startAngle | **float** | Ángulo en grados medido en sentido horario desde el eje X hasta el punto inicial del sector |
| sweepAngle | **float** | Ángulo en grados medido en sentido horario desde el **startAngle** hasta el punto final del sector |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Pen](../../pen/)
* Clase [Graphics](../)
* Clase [Rectangle](../../rectangle/)
* Clase [RectangleF](../../rectanglef/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)