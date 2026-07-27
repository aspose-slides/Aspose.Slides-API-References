---
title: DrawCurve()
second_title: Referência da API Aspose.Slides para C++
description: Desenha uma spline usando a pen especificada.
type: docs
weight: 794
url: /pt/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) method


Desenha uma spline usando a pen especificada.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Uma pen a ser usada ao desenhar a spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de pontos que determina a spline |
| tension | **float** | Valor que especifica a tensão da spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) method


Desenha uma spline usando a pen especificada.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Uma pen a ser usada ao desenhar a spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de pontos que determina a spline |
| tension | **float** | Valor que especifica a tensão da spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) method


Desenha uma spline usando a pen especificada.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Uma pen a ser usada ao desenhar a spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de pontos que determina a spline |
| offset | **int32_t** | Deslocamento a partir do primeiro elemento no array **points** |
| numberOfSegments | **int32_t** | Número de segmentos a incluir na curva |
| tension | **float** | Valor que especifica a tensão da spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) method


Desenha uma spline usando a pen especificada.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Uma pen a ser usada ao desenhar a spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de pontos que determina a spline |
| offset | **int32_t** | Deslocamento a partir do primeiro elemento no array **points** |
| numberOfSegments | **int32_t** | Número de segmentos a incluir na curva |
| tension | **float** | Valor que especifica a tensão da spline |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)