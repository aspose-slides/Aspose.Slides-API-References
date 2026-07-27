---
title: QuadraticBezierTo()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona curva Bézier quadrática ao final do caminho
type: docs
weight: 105
url: /pt/aspose.slides/igeometrypath/quadraticbezierto/
---
## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) método

Adiciona uma curva Bézier quadrática ao final do caminho

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Ponto de direção |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Ponto final |

## IGeometryPath::QuadraticBezierTo(float, float, float, float) método

Adiciona uma curva Bézier quadrática ao final do caminho

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 | **float** | Coordenada X do ponto de direção |
| y1 | **float** | Coordenada Y do ponto de direção |
| x2 | **float** | Coordenada X do ponto final |
| y2 | **float** | Coordenada Y do ponto final |

## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) método

Adiciona uma curva Bézier quadrática ao local especificado do caminho

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Ponto de direção |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Ponto final |
| index | **uint32_t** | Índice do segmento em PathData |

## IGeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) método

Adiciona uma curva Bézier quadrática ao local especificado do caminho

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 | **float** | Coordenada X do ponto de direção |
| y1 | **float** | Coordenada Y do ponto de direção |
| x2 | **float** | Coordenada X do ponto final |
| y2 | **float** | Coordenada Y do ponto final |
| index | **uint32_t** | Índice do segmento em PathData |

## Veja Também

* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IGeometryPath](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)