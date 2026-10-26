---
title: CubicBezierTo()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona curva cúbica de Bézier ao final do caminho
type: docs
weight: 92
url: /pt/aspose.slides/igeometrypath/cubicbezierto/
---
## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) method

Adiciona curva cúbica de Bézier ao final do caminho

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Primeiro ponto de direção |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Segundo ponto de direção |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Ponto final |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float) method

Adiciona curva cúbica de Bézier ao final do caminho

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 | **float** | Coordenada X do primeiro ponto de direção |
| y1 | **float** | Coordenada Y do primeiro ponto de direção |
| x2 | **float** | Coordenada X do segundo ponto de direção |
| y2 | **float** | Coordenada Y do segundo ponto de direção |
| x3 | **float** | Coordenada X do ponto final |
| y3 | **float** | Coordenada Y do ponto final |

## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) method

Adiciona curva cúbica de Bézier ao local especificado do caminho

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Primeiro ponto de direção |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Segundo ponto de direção |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Ponto final |
| index | **uint32_t** | Índice do segmento em PathData |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) method

Adiciona curva cúbica de Bézier ao local especificado do caminho

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 | **float** | Coordenada X do primeiro ponto de direção |
| y1 | **float** | Coordenada Y do primeiro ponto de direção |
| x2 | **float** | Coordenada X do segundo ponto de direção |
| y2 | **float** | Coordenada Y do segundo ponto de direção |
| x3 | **float** | Coordenada X do ponto final |
| y3 | **float** | Coordenada Y do ponto final |
| index | **uint32_t** | Índice do segmento em PathData |

## Ver Também

* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IGeometryPath](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)