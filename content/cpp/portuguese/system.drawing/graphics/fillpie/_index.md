---
title: FillPie()
second_title: Referência da API Aspose.Slides para C++
description: Preenche a fatia especificada usando o brush especificado na superfície representada pelo objeto atual.
type: docs
weight: 274
url: /pt/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) método


Preenche a fatia especificada usando o brush especificado na superfície representada pelo objeto atual.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Um brush a ser usado ao preencher a fatia |
| x | int | A coordenada X do canto superior esquerdo do retângulo que define a elipse |
| y | int | A coordenada Y do canto superior esquerdo do retângulo que define a elipse |
| width | int | A largura do retângulo que define a elipse |
| height | int | A altura do retângulo que define a elipse |
| startAngle | int | Ângulo em graus medido no sentido horário a partir do eixo X até o ponto inicial da fatia |
| sweepAngle | int | Ângulo em graus medido no sentido horário a partir do **startAngle** até o ponto final da fatia |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) método


Preenche a fatia especificada usando o brush especificado na superfície representada pelo objeto atual.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Um brush a ser usado ao preencher a fatia |
| x | **float** | A coordenada X do canto superior esquerdo do retângulo que define a elipse |
| y | **float** | A coordenada Y do canto superior esquerdo do retângulo que define a elipse |
| width | **float** | A largura do retângulo que define a elipse |
| height | **float** | A altura do retângulo que define a elipse |
| startAngle | **float** | Ângulo em graus medido no sentido horário a partir do eixo X até o ponto inicial da fatia |
| sweepAngle | **float** | Ângulo em graus medido no sentido horário a partir do **startAngle** até o ponto final da fatia |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) método


Preenche a fatia especificada usando o brush especificado na superfície representada pelo objeto atual.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Um brush a ser usado ao preencher a fatia |
| rect | [Rectangle](../../rectangle/) | O retângulo que define a elipse |
| startAngle | **float** | Ângulo em graus medido no sentido horário a partir do eixo X até o ponto inicial da fatia |
| sweepAngle | **float** | Ângulo em graus medido no sentido horário a partir do **startAngle** até o ponto final da fatia |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Brush](../../brush/)
* Classe [Graphics](../)
* Classe [Rectangle](../../rectangle/)
* Espaço de nomes [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)