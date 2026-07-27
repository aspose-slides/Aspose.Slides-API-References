---
title: DrawCurve()
second_title: Referencia de API de Aspose.Slides para C++
description: Dibuja una spline usando la pluma especificada.
type: docs
weight: 794
url: /es/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) método


Dibuja una spline usando la pluma especificada.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una Pen a usar al dibujar la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de puntos que determina la spline |
| tension | **float** | Valor que especifica la tensión de la spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) método


Dibuja una spline usando la pluma especificada.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una Pen a usar al dibujar la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de puntos que determina la spline |
| tension | **float** | Valor que especifica la tensión de la spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) método


Dibuja una spline usando la pluma especificada.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una Pen a usar al dibujar la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de puntos que determina la spline |
| offset | **int32_t** | Desplazamiento desde el primer elemento del arreglo **points** |
| numberOfSegments | **int32_t** | Número de segmentos que incluir en la curva |
| tension | **float** | Valor que especifica la tensión de la spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) método


Dibuja una spline usando la pluma especificada.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una Pen a usar al dibujar la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de puntos que determina la spline |
| offset | **int32_t** | Desplazamiento desde el primer elemento del arreglo **points** |
| numberOfSegments | **int32_t** | Número de segmentos que incluir en la curva |
| tension | **float** | Valor que especifica la tensión de la spline |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)