---
title: QuadraticBezierTo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega una curva Bézier cuadrática al final de la trayectoria
type: docs
weight: 105
url: /es/aspose.slides/igeometrypath/quadraticbezierto/
---
## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) method

Agrega una curva Bézier cuadrática al final de la trayectoria

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto de dirección |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto final |

## IGeometryPath::QuadraticBezierTo(float, float, float, float) method

Agrega una curva Bézier cuadrática al final de la trayectoria

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 | **float** | Coordenada X del punto de dirección |
| y1 | **float** | Coordenada Y del punto de dirección |
| x2 | **float** | Coordenada X del punto final |
| y2 | **float** | Coordenada Y del punto final |

## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) method

Agrega una curva Bézier cuadrática al lugar especificado de la trayectoria

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto de dirección |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Punto final |
| index | **uint32_t** | Índice del segmento en PathData |

## IGeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) method

Agrega una curva Bézier cuadrática al lugar especificado de la trayectoria

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 | **float** | Coordenada X del punto de dirección |
| y1 | **float** | Coordenada Y del punto de dirección |
| x2 | **float** | Coordenada X del punto final |
| y2 | **float** | Coordenada Y del punto final |
| index | **uint32_t** | Índice del segmento en PathData |

## Ver también

* Clase [PointF](../../../system.drawing/pointf/)
* Clase [IGeometryPath](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)