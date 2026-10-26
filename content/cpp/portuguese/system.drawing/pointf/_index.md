---
title: PointF
second_title: Referência da API Aspose.Slides para C++
description: "Representa um par de coordenadas X e Y de ponto em um plano bidimensional de ponto flutuante de precisão simples. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 222
url: /pt/system.drawing/pointf/
---
## PointF classe

Representa um par de coordenadas X e Y de ponto em um plano bidimensional, usando ponto flutuante de precisão simples. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../../system/smartptr/) para gerenciar objetos deste tipo.

```cpp
class PointF
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Adiciona os valores de largura e altura do objeto [SizeF](../sizef/) especificado aos valores das coordenadas X e Y do objeto [PointF](./) especificado, respectivamente. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Adiciona os valores de largura e altura do objeto [Size](../size/) especificado aos valores das coordenadas X e Y do objeto [PointF](./) especificado, respectivamente. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Determina se o objeto atual e o objeto especificado são iguais, ou seja, representam o mesmo par de valores de coordenadas X e Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se ambos os valores das coordenadas X e Y são iguais a 0. |
| **float** [get_X](./get_x/)() const | Retorna o valor da coordenada X representado pelo objeto atual. |
| **float** [get_Y](./get_y/)() const | Retorna o valor da coordenada Y representado pelo objeto atual. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
| **bool** [IsNull](./isnull/)() const | Sempre retorna false. |
| explicit  [operator bool](./operator_bool/)() | Sempre retorna true. |
|  [PointF](./pointf/)() | Constrói um novo objeto [PointF](./) e inicializa seus valores das coordenadas X e Y com 0. |
|  [PointF](./pointf/)(**float**, **float**) | Constrói um novo objeto [PointF](./) e o inicializa com os valores especificados. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Constrói um novo objeto [PointF](./) e inicializa seus valores das coordenadas X e Y com os valores de largura e altura do objeto [SizeF](../sizef/) especificado, respectivamente. |
| void [set_X](./set_x/)(**float**) | Define o valor da coordenada X representado pelo objeto atual. |
| void [set_Y](./set_y/)(**float**) | Define o valor da coordenada Y representado pelo objeto atual. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Subtrai os valores de largura e altura do objeto [SizeF](../sizef/) especificado dos valores das coordenadas X e Y do objeto [PointF](./) especificado, respectivamente. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Subtrai os valores de largura e altura do objeto [Size](../size/) especificado dos valores das coordenadas X e Y do objeto [PointF](./) especificado, respectivamente. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Retorna a representação em forma de string do par de valores das coordenadas X e Y representado pelo objeto atual. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [Empty](./empty/) | Uma instância vazia da classe [PointF](./) cujos valores das coordenadas X e Y são 0. |

## Ver também

* Espaço de nomes [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)