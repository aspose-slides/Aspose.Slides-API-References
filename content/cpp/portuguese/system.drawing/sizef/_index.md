---
title: SizeF
second_title: Referência da API Aspose.Slides para C++
description: "Representa um par de valores de ponto flutuante de precisão simples que representam a largura e a altura de uma imagem. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 287
url: /pt/system.drawing/sizef/
---
## SizeF classe

Representa um par de valores de ponto flutuante de precisão simples que representam a largura e a altura de uma imagem. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../../system/smartptr/) para gerenciar objetos desse tipo.

```cpp
class SizeF
```

## Métodos

| Method | Description |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Retorna um novo objeto [SizeF](./) que é a soma dos objetos [SizeF](./) especificados, ou seja, cujo valor de largura é igual à soma dos valores de largura dos objetos especificados e o valor de altura é igual à soma dos valores de altura dos objetos especificados. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Determina se o objeto atual e o objeto especificado são iguais, ou seja, representam o mesmo par de valores de largura e altura. |
| **float** [get_Height](./get_height/)() const | Retorna o valor da altura representado pelo objeto atual. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se os valores de largura e altura são iguais a 0. |
| **float** [get_Width](./get_width/)() const | Retorna o valor da largura representado pelo objeto atual. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
| [operator PointF](./operator_pointf/)() const | Converte o objeto atual para uma instância do objeto [Point](../point/) inicializando sua coordenada X e Y com os valores de largura e altura do objeto atual, respectivamente. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Adiciona os valores de largura e altura do objeto [SizeF](./) especificado aos valores de largura e altura do objeto [SizeF](./) atual, respectivamente. |
| void [set_Height](./set_height/)(**float**) | Define o valor da altura representado pelo objeto atual. |
| void [set_Width](./set_width/)(**float**) | Define o valor da largura representado pelo objeto atual. |
| [SizeF](./sizef/)() | Constrói um novo objeto [SizeF](./) e inicializa seus valores de largura e altura com 0. |
| [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Constrói um novo objeto [SizeF](./) e inicializa seus valores de largura e altura com os valores das coordenadas X e Y do ponto especificado, respectivamente. |
| [SizeF](./sizef/)(**float**, **float**) | Constrói um novo objeto [SizeF](./) e o inicializa com o valor especificado. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Retorna um novo objeto [SizeF](./) que é o resultado da subtração de **size2** de **size1**, ou seja, cujo valor de largura é o resultado da subtração do valor de largura de **size2** do valor de largura de **size1** e o valor de altura é o resultado da subtração do valor de altura de **size2** do valor de altura de **size1**. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Converte o objeto atual para uma instância do objeto [Point](../point/) inicializando sua coordenada X e Y com os valores de largura e altura do objeto atual, respectivamente. |
| [Size](../size/) [ToSize](./tosize/)() const | Constrói um objeto [Size](../size/) a partir do objeto [SizeF](./) atual truncando os valores de largura e altura do objeto [SizeF](./) para os próximos valores inteiros inferiores. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Retorna a representação em string do par de valores de largura e altura representados pelo objeto atual. |

## Campos

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Uma instância vazia da classe [SizeF](./) cujo valores de largura e altura são 0. |

## Ver também

* Espaço de nomes [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)