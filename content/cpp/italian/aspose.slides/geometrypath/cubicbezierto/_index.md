---
title: CubicBezierTo()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una curva Bézier cubica alla fine del percorso
type: docs
weight: 105
url: /it/aspose.slides/geometrypath/cubicbezierto/
---
## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) method

Aggiunge una curva Bézier cubica alla fine del percorso

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Primo punto di direzione |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Secondo punto di direzione |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto finale |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float) method

Aggiunge una curva Bézier cubica alla fine del percorso

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | **float** | Coordinata X del primo punto di direzione |
| y1 | **float** | Coordinata Y del primo punto di direzione |
| x2 | **float** | Coordinata X del secondo punto di direzione |
| y2 | **float** | Coordinata Y del secondo punto di direzione |
| x3 | **float** | Coordinata X del punto finale |
| y3 | **float** | Coordinata Y del punto finale |

## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) method

Aggiunge una curva Bézier cubica nella posizione specificata del percorso

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Primo punto di direzione |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Secondo punto di direzione |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto finale |
| index | **uint32_t** | Indice del segmento in PathData |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) method

Aggiunge una curva Bézier cubica nella posizione specificata del percorso

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 | **float** | Coordinata X del primo punto di direzione |
| y1 | **float** | Coordinata Y del primo punto di direzione |
| x2 | **float** | Coordinata X del secondo punto di direzione |
| y2 | **float** | Coordinata Y del secondo punto di direzione |
| x3 | **float** | Coordinata X del punto finale |
| y3 | **float** | Coordinata Y del punto finale |
| index | **uint32_t** | Indice del segmento in PathData |

## Vedi anche

* Classe [PointF](../../../system.drawing/pointf/)
* Classe [GeometryPath](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)