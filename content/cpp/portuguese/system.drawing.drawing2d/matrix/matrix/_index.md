---
title: Matrix()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância da classe Matrix que representa uma matriz identidade.
type: docs
weight: 1
url: /pt/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() construtor

Constrói uma nova instância da classe [Matrix](../) que representa uma matriz identidade.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) construtor

Constrói uma nova instância da classe [Matrix](../) e a inicializa com os valores especificados.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| m11 | **float** | O valor da 1ª linha 1ª coluna |
| m12 | **float** | O valor da 1ª linha 2ª coluna |
| m21 | **float** | O valor da 2ª linha 1ª coluna |
| m22 | **float** | O valor da 2ª linha 2ª coluna |
| dx | **float** | O valor da 3ª linha 1ª coluna |
| dy | **float** | O valor da 3ª linha 2ª coluna |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) construtor

Constrói uma nova instância da classe [Matrix](../) para a transformação geométrica definida pelo retângulo especificado e pela matriz de pontos.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) construtor

Constrói uma nova instância da classe [Matrix](../) para a transformação geométrica definida pelo retângulo especificado e pela matriz de pontos.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Matrix](../)
* Classe [Rectangle](../../../system.drawing/rectangle/)
* Classe [Point](../../../system.drawing/point/)
* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [PointF](../../../system.drawing/pointf/)
* Espaço de nomes [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)