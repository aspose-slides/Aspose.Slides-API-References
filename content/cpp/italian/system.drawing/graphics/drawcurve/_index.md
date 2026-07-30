---
title: DrawCurve()
second_title: Riferimento API di Aspose.Slides per C++
description: Disegna una spline usando la penna specificata.
type: docs
weight: 794
url: /it/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) method

Disegna una spline usando la penna specificata.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da usare quando si disegna la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) di punti che determinano la spline |
| tension | **float** | Valore che specifica la tensione della spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) method

Disegna una spline usando la penna specificata.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da usare quando si disegna la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) di punti che determinano la spline |
| tension | **float** | Valore che specifica la tensione della spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) method

Disegna una spline usando la penna specificata.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da usare quando si disegna la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) di punti che determinano la spline |
| offset | **int32_t** | Offset dal primo elemento nell'array **points** |
| numberOfSegments | **int32_t** | Numero di segmenti da includere nella curva |
| tension | **float** | Valore che specifica la tensione della spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) method

Disegna una spline usando la penna specificata.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Una penna da usare quando si disegna la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) di punti che determinano la spline |
| offset | **int32_t** | Offset dal primo elemento nell'array **points** |
| numberOfSegments | **int32_t** | Numero di segmenti da includere nella curva |
| tension | **float** | Valore che specifica la tensione della spline |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Pen](../../pen/)
* Classe [Point](../../point/)
* Classe [Graphics](../)
* Classe [PointF](../../pointf/)
* Spazio dei nomi [System::Drawing](../../)
* Library [Aspose.Slides](../../../)