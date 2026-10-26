---
title: CubicBezierTo()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge una curva Bezier cubica alla fine del percorso
type: docs
weight: 92
url: /it/aspose.slides/igeometrypath/cubicbezierto/
---
## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) metodo


Aggiunge una curva Bezier cubica alla fine del percorso

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | First direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Second direction point |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float) metodo


Aggiunge una curva Bezier cubica alla fine del percorso

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |

## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) metodo


Aggiunge una curva Bezier cubica al punto specificato del percorso

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | First direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Second direction point |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |
| index | **uint32_t** | Index of segment in PathData |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) metodo


Aggiunge una curva Bezier cubica al punto specificato del percorso

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |
| index | **uint32_t** | Index of segment in PathData |

## Vedi anche

* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IGeometryPath](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)