---
title: Flatten()
second_title: Referência da API Aspose.Slides para C++
description: Aplana cada curva no caminho convertendo-as em uma série de linhas conectadas. O valor de planicidade de 0.25 é usado.
type: docs
weight: 391
url: /pt/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() método

Aplana cada curva no caminho convertendo-as em uma série de linhas conectadas. O valor de planicidade de 0.25 é usado.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) método

Aplana cada curva no caminho convertendo-as em uma série de linhas conectadas. O valor de planicidade de 0.25 é usado.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | A matriz de transformação a ser aplicada ao caminho antes da aplainação |

## GraphicsPath::Flatten(const MatrixPtr\&, float) método

Aplana cada curva no caminho convertendo-as em uma série de linhas conectadas.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | A matriz de transformação a ser aplicada ao caminho antes da aplainação |
| flatness | **float** | Especifica o erro máximo permitido entre a curva e sua aproximação aplainada |

## Veja Também

* Typedef [MatrixPtr](../../matrixptr/)
* Classe [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Biblioteca [Aspose.Slides](../../../)