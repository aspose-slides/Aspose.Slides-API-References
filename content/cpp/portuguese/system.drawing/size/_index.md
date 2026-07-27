---
title: Size
second_title: Referência da API Aspose.Slides para C++
description: "Representa um par de valores inteiros que representam a largura e a altura de uma imagem. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 274
url: /pt/system.drawing/size/
---
## Classe Size

Representa um par de valores inteiros que representam a largura e a altura de uma imagem. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../../system/smartptr/) para gerenciar objetos deste tipo.

```cpp
class Size
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Retorna um novo objeto [Size](./) que é a soma do objeto [Size](./) especificado, ou seja, cujo valor de largura é igual à soma dos valores de largura dos objetos especificados e o valor de altura é igual à soma dos valores de altura dos objetos especificados. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Constrói um objeto [Size](./) a partir do objeto [SizeF](../sizef/) especificado, arredondando os valores de largura e altura do objeto [SizeF](../sizef/) para os próximos valores inteiros superiores. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Determina se o objeto atual e o objeto especificado são iguais, ou seja, representam o mesmo par de valores de largura e altura. |
| int [get_Height](./get_height/)() const | Retorna o valor da altura representado pelo objeto atual. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se ambos os valores de largura e altura são iguais a 0. |
| int [get_Width](./get_width/)() const | Retorna o valor da largura representado pelo objeto atual. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
|  [operator Point](./operator_point/)() const | Constrói uma instância do objeto [Point](../point/) e inicializa sua coordenada X e Y com os valores de largura e altura do objeto atual, respectivamente. |
|  [operator SizeF](./operator_sizef/)() const | Constrói uma instância do objeto [SizeF](../sizef/) e a inicializa com os valores de largura e altura do objeto [Size](./) atual. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Constrói um objeto [Size](./) a partir do objeto [SizeF](../sizef/) especificado, arredondando os valores de largura e altura do objeto [SizeF](../sizef/) para os valores inteiros mais próximos. |
| void [set_Height](./set_height/)(int) | Define o valor da altura representado pelo objeto atual. |
| void [set_Width](./set_width/)(int) | Define o valor da largura representado pelo objeto atual. |
|  [Size](./size/)() | Constrói um novo objeto [Size](./) e inicializa seus valores de largura e altura com 0. |
|  [Size](./size/)(const [Point](../point/)\&) | Constrói um novo objeto [Size](./) e inicializa seus valores de largura e altura com os valores das coordenadas X e Y do ponto especificado, respectivamente. |
|  [Size](./size/)(int, int) | Constrói um novo objeto [Size](./) e o inicializa com o valor especificado. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Retorna um novo objeto [Size](./) que é o resultado da subtração de **size2** de **size1**, ou seja, cujo valor de largura é o resultado da subtração do valor de largura de **size2** do valor de largura de **size1**, e o valor de altura é o resultado da subtração do valor de altura de **size2** do valor de altura de **size1**. |
| [String](../../system/string/) [ToString](./tostring/)() const | Retorna a representação em cadeia de caracteres do par de valores de largura e altura representados pelo objeto atual. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Constrói um objeto [Size](./) a partir do objeto [SizeF](../sizef/) especificado, truncando os valores de largura e altura do objeto [SizeF](../sizef/) para os próximos valores inteiros inferiores. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [Empty](./empty/) | Uma instância vazia da classe [Size](./) cujos valores de largura e altura são 0. |

## Veja Também

* Espaço de nomes [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)