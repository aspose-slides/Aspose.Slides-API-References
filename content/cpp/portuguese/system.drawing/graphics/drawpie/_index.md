---
title: DrawPie()
second_title: Referência da API Aspose.Slides para C++
description: Desenha o setor especificado usando a caneta especificada na superfície representada pelo objeto atual.
type: docs
weight: 261
url: /pt/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) método

Desenha o setor especificado usando a caneta especificada na superfície representada pelo objeto atual.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Uma caneta a ser usada ao desenhar o setor |
| x | **int32_t** | A coordenada X do canto superior esquerdo do retângulo que define a elipse |
| y | **int32_t** | A coordenada Y do canto superior esquerdo do retângulo que define a elipse |
| width | **int32_t** | A largura do retângulo que define a elipse |
| height | **int32_t** | A altura do retângulo que define a elipse |
| startAngle | **int32_t** | Ângulo em graus medido no sentido horário a partir do eixo X até o ponto inicial do setor |
| sweepAngle | **int32_t** | Ângulo em graus medido no sentido horário a partir do **startAngle** até o ponto final do setor |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) método

Desenha o setor especificado usando a caneta especificada na superfície representada pelo objeto atual.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Uma caneta a ser usada ao desenhar o setor |
| x | **float** | A coordenada X do canto superior esquerdo do retângulo que define a elipse |
| y | **float** | A coordenada Y do canto superior esquerdo do retângulo que define a elipse |
| width | **float** | A largura do retângulo que define a elipse |
| height | **float** | A altura do retângulo que define a elipse |
| startAngle | **float** | Ângulo em graus medido no sentido horário a partir do eixo X até o ponto inicial do setor |
| sweepAngle | **float** | Ângulo em graus medido no sentido horário a partir do **startAngle** até o ponto final do setor |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) método

Desenha o setor especificado usando a caneta especificada na superfície representada pelo objeto atual.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Uma caneta a ser usada ao desenhar o setor |
| rect | [Rectangle](../../rectangle/) | O retângulo que define a elipse |
| startAngle | **float** | Ângulo em graus medido no sentido horário a partir do eixo X até o ponto inicial do setor |
| sweepAngle | **float** | Ângulo em graus medido no sentido horário a partir do **startAngle** até o ponto final do setor |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) método

Desenha o setor especificado usando a caneta especificada na superfície representada pelo objeto atual.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Uma caneta a ser usada ao desenhar o setor |
| rect | [RectangleF](../../rectanglef/) | O retângulo que define a elipse |
| startAngle | **float** | Ângulo em graus medido no sentido horário a partir do eixo X até o ponto inicial do setor |
| sweepAngle | **float** | Ângulo em graus medido no sentido horário a partir do **startAngle** até o ponto final do setor |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)