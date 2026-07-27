---
title: FillPie()
second_title: Referencia de API de Aspose.Slides para C++
description: Rellena el pastel especificado usando el pincel especificado en la superficie representada por el objeto actual.
type: docs
weight: 274
url: /es/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) método


Rellena el pastel especificado usando el pincel especificado en la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pincel que se usará al rellenar el pastel |
| x | int | La coordenada X de la esquina superior izquierda del rectángulo que define la elipse |
| y | int | La coordenada Y de la esquina superior izquierda del rectángulo que define la elipse |
| width | int | El ancho del rectángulo que define la elipse |
| height | int | La altura del rectángulo que define la elipse |
| startAngle | int | Ángulo en grados medido en sentido horario desde el eje X hasta el punto inicial del pastel |
| sweepAngle | int | Ángulo en grados medido en sentido horario desde el **startAngle** hasta el punto final del pastel |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) método


Rellena el pastel especificado usando el pincel especificado en la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pincel que se usará al rellenar el pastel |
| x | **float** | La coordenada X de la esquina superior izquierda del rectángulo que define la elipse |
| y | **float** | La coordenada Y de la esquina superior izquierda del rectángulo que define la elipse |
| width | **float** | El ancho del rectángulo que define la elipse |
| height | **float** | La altura del rectángulo que define la elipse |
| startAngle | **float** | Ángulo en grados medido en sentido horario desde el eje X hasta el punto inicial del pastel |
| sweepAngle | **float** | Ángulo en grados medido en sentido horario desde el **startAngle** hasta el punto final del pastel |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) método


Rellena el pastel especificado usando el pincel especificado en la superficie representada por el objeto actual.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un pincel que se usará al rellenar el pastel |
| rect | [Rectangle](../../rectangle/) | El rectángulo que define la elipse |
| startAngle | **float** | Ángulo en grados medido en sentido horario desde el eje X hasta el punto inicial del pastel |
| sweepAngle | **float** | Ángulo en grados medido en sentido horario desde el **startAngle** hasta el punto final del pastel |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)