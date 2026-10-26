---
title: AddArc()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona o arco elíptico especificado ao caminho representado pelo objeto atual.
type: docs
weight: 183
url: /pt/system.drawing.drawing2d/graphicspath/addarc/
---
## GraphicsPath::AddArc(float, float, float, float, float, float) método

Adiciona o arco elíptico especificado ao caminho representado pelo objeto atual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada X do canto superior esquerdo do retângulo que delimita a elipse da qual o arco é desenhado |
| y | **float** | A coordenada Y do canto superior esquerdo do retângulo que delimita a elipse da qual o arco é desenhado |
| width | **float** | A largura do retângulo que delimita a elipse da qual o arco é desenhado |
| height | **float** | A altura do retângulo que delimita a elipse da qual o arco é desenhado |
| startAngle | **float** | Especifica o ângulo inicial do arco em graus, medido no sentido horário a partir do eixo X |
| sweepAngle | **float** | Especifica o ângulo entre o ângulo inicial e o final do arco |

## GraphicsPath::AddArc(int, int, int, int, float, float) método

Adiciona o arco elíptico especificado ao caminho representado pelo objeto atual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | int | A coordenada X do canto superior esquerdo do retângulo que delimita a elipse da qual o arco é desenhado |
| y | int | A coordenada Y do canto superior esquerdo do retângulo que delimita a elipse da qual o arco é desenhado |
| width | int | A largura do retângulo que delimita a elipse da qual o arco é desenhado |
| height | int | A altura do retângulo que delimita a elipse da qual o arco é desenhado |
| startAngle | **float** | Especifica o ângulo inicial do arco em graus, medido no sentido horário a partir do eixo X |
| sweepAngle | **float** | Especifica o ângulo entre o ângulo inicial e o final do arco |

## GraphicsPath::AddArc(const RectangleF\&, float, float) método

Adiciona o arco elíptico especificado ao caminho representado pelo objeto atual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const RectangleF &rect, float startAngle, float sweepAngle)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | O retângulo que delimita a elipse da qual o arco é desenhado |
| startAngle | **float** | Especifica o ângulo inicial do arco em graus, medido no sentido horário a partir do eixo X |
| sweepAngle | **float** | Especifica o ângulo entre o ângulo inicial e o final do arco |

## GraphicsPath::AddArc(const Rectangle\&, float, float) método

Adiciona o arco elíptico especificado ao caminho representado pelo objeto atual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const Rectangle &rect, float startAngle, float sweepAngle)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | O retângulo que delimita a elipse da qual o arco é desenhado |
| startAngle | **float** | Especifica o ângulo inicial do arco em graus, medido no sentido horário a partir do eixo X |
| sweepAngle | **float** | Especifica o ângulo entre o ângulo inicial e o final do arco |

## Veja também

* Classe [GraphicsPath](../)
* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [Rectangle](../../../system.drawing/rectangle/)
* Namespace [System::Drawing::Drawing2D](../../)
* Biblioteca [Aspose.Slides](../../../)