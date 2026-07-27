---
title: Point
second_title: Referência da API Aspose.Slides para C++
description: "Representa um par de coordenadas inteiras X e Y de um ponto em um plano bidimensional. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 209
url: /pt/system.drawing/point/
---
## Point classe

Representa um par de coordenadas inteiras X e Y de um ponto em um plano bidimensional. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../../system/smartptr/) para gerenciar objetos desse tipo.

```cpp
class Point
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Adiciona os valores de largura e altura do objeto [Size](../size/) especificado aos valores das coordenadas X e Y do objeto [Point](./) especificado, respectivamente. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Constrói um objeto [Point](./) a partir do objeto [PointF](../pointf/) especificado, arredondando os valores das coordenadas X e Y do objeto [PointF](../pointf/) para os próximos valores inteiros superiores. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Determina se o objeto atual e o objeto especificado são iguais, ou seja, representam o mesmo par de valores de coordenadas X e Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina se ambos os valores das coordenadas X e Y são iguais a 0. |
| int [get_X](./get_x/)() const | Retorna o valor da coordenada X representado pelo objeto atual. |
| int [get_Y](./get_y/)() const | Retorna o valor da coordenada Y representado pelo objeto atual. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
| size_t [getStdHash](./getstdhash/)() const | Retorna um valor hash para o objeto atual. |
| **bool** [IsNull](./isnull/)() const | Sempre retorna false. |
| void [Offset](./offset/)(int, int) | Compensa o valor das coordenadas X e Y representado pelo objeto atual pelos valores especificados. |
| void [Offset](./offset/)([Point](./)) | Compensa as coordenadas X e Y representadas pelo objeto atual pelos valores das coordenadas X e Y do objeto [Point](./) especificado, respectivamente. |
| [operator PointF](./operator_pointf/)() const | Constrói uma instância do objeto [PointF](../pointf/) e a inicializa com os valores das coordenadas X e Y do objeto [Point](./) atual. |
| [operator Size](./operator_size/)() const | Constrói uma instância do objeto [Size](../size/) e inicializa seus valores de largura e altura com os valores das coordenadas X e Y representados pelo objeto atual, respectivamente. |
| [Point](./point/)() | Constrói um novo objeto [Point](./) e inicializa seus valores das coordenadas X e Y com 0. |
| [Point](./point/)(int, int) | Constrói um novo objeto [Point](./) e o inicializa com os valores especificados. |
| [Point](./point/)(const [Size](../size/)\&) | Constrói um novo objeto [Point](./) e inicializa seus valores das coordenadas X e Y com os valores de largura e altura do objeto [SizeF](../sizef/) especificado, respectivamente. |
| [Point](./point/)(int) | Constrói um novo objeto [Point](./) e inicializa seu valor da coordenada X com um valor formado pelos 16 bits mais altos do inteiro de 32 bits especificado e seu valor da coordenada Y com um valor formado pelos 16 bits mais baixos do mesmo inteiro de 32 bits. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Constrói um objeto [Point](./) a partir do objeto [PointF](../pointf/) especificado, arredondando os valores das coordenadas X e Y do objeto [PointF](../pointf/) para os valores inteiros mais próximos. |
| void [set_X](./set_x/)(int) | Define o valor da coordenada X representado pelo objeto atual. |
| void [set_Y](./set_y/)(int) | Define o valor da coordenada Y representado pelo objeto atual. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Subtrai os valores de largura e altura do objeto [Size](../size/) especificado dos valores das coordenadas X e Y do objeto [Point](./) especificado, respectivamente. |
| [String](../../system/string/) [ToString](./tostring/)() const | Retorna a representação em string do par de valores das coordenadas X e Y representados pelo objeto atual. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Constrói um objeto [Point](./) a partir do objeto [PointF](../pointf/) especificado, truncando os valores das coordenadas X e Y do objeto [PointF](../pointf/) para os próximos valores inteiros inferiores. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [Empty](./empty/) | Uma instância vazia da classe [Point](./) cujos valores das coordenadas X e Y são 0. |

## Veja Também

* Namespace [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)