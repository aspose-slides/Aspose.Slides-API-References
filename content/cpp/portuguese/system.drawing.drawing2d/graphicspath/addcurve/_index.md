---
title: AddCurve()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona a curva especificada ao caminho representado pelo objeto atual.
type: docs
weight: 274
url: /pt/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) method

Adiciona a curva especificada ao caminho representado pelo objeto atual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Pontos que especificam a curva |
| tension | **float** | Especifica a quantidade que a curva se curva entre os pontos de controle |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) method

Adiciona a curva especificada ao caminho representado pelo objeto atual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Pontos que especificam a curva |
| tension | **float** | Especifica a quantidade que a curva se curva entre os pontos de controle |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) method

Adiciona a curva especificada ao caminho representado pelo objeto atual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Pontos que especificam a curva |
| offset | int | O índice do ponto em **points** que é usado como o ponto de partida da curva |
| number_of_segments | int | O número de segmentos usados para desenhar a curva |
| tension | **float** | Especifica a quantidade que a curva se curva entre os pontos de controle |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) method

Adiciona a curva especificada ao caminho representado pelo objeto atual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Pontos que especificam a curva |
| offset | int | O índice do ponto em **points** que é usado como o ponto de partida da curva |
| number_of_segments | int | O número de segmentos usados para desenhar a curva |
| tension | **float** | Especifica a quantidade que a curva se curva entre os pontos de controle |

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)