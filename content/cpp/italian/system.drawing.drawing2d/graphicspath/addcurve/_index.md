---
title: AddCurve()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge la curva specificata al percorso rappresentato dall'oggetto corrente.
type: docs
weight: 274
url: /it/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) metodo


Aggiunge la curva specificata al percorso rappresentato dall'oggetto corrente.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punti che specificano la curva |
| tension | **float** | Specifica la quantità con cui la curva si piega tra i punti di controllo |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) metodo


Aggiunge la curva specificata al percorso rappresentato dall'oggetto corrente.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punti che specificano la curva |
| tension | **float** | Specifica la quantità con cui la curva si piega tra i punti di controllo |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) metodo


Aggiunge la curva specificata al percorso rappresentato dall'oggetto corrente.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Punti che specificano la curva |
| offset | int | L'indice del punto in **points** che viene usato come punto di partenza della curva |
| number_of_segments | int | Il numero di segmenti usati per disegnare la curva |
| tension | **float** | Specifica la quantità con cui la curva si piega tra i punti di controllo |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) metodo


Aggiunge la curva specificata al percorso rappresentato dall'oggetto corrente.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Punti che specificano la curva |
| offset | int | L'indice del punto in **points** che viene usato come punto di partenza della curva |
| number_of_segments | int | Il numero di segmenti usati per disegnare la curva |
| tension | **float** | Specifica la quantità con cui la curva si piega tra i punti di controllo |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [GraphicsPath](../)
* Classe [Point](../../../system.drawing/point/)
* Spazio dei nomi [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)