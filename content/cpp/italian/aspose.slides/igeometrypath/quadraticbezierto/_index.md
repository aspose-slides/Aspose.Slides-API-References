---
title: QuadraticBezierTo()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una curva Bézier quadratica alla fine del percorso
type: docs
weight: 105
url: /it/aspose.slides/igeometrypath/quadraticbezierto/
---
## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) metodo


Aggiunge una curva Bézier quadratica alla fine del percorso

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto di direzione |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto finale |

## IGeometryPath::QuadraticBezierTo(float, float, float, float) metodo


Aggiunge una curva Bézier quadratica alla fine del percorso

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | **float** | Coordinata X del punto di direzione |
| y1 | **float** | Coordinata Y del punto di direzione |
| x2 | **float** | Coordinata X del punto finale |
| y2 | **float** | Coordinata Y del punto finale |

## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) metodo


Aggiunge una curva Bézier quadratica nella posizione specificata del percorso

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto di direzione |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto finale |
| index | **uint32_t** | Indice del segmento in PathData |

## IGeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) metodo


Aggiunge una curva Bézier quadratica nella posizione specificata del percorso

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | **float** | Coordinata X del punto di direzione |
| y1 | **float** | Coordinata Y del punto di direzione |
| x2 | **float** | Coordinata X del punto finale |
| y2 | **float** | Coordinata Y del punto finale |
| index | **uint32_t** | Indice del segmento in PathData |

## Vedi anche

* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IGeometryPath](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)