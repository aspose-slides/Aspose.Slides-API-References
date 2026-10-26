---
title: Subtract()
second_title: Referência da API Aspose.Slides para C++
description: Subtrai os valores de largura e altura do objeto Size especificado dos valores das coordenadas X e Y do objeto Point especificado, respectivamente.
type: docs
weight: 196
url: /pt/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) método

Subtrai os valores de largura e altura do objeto [Size](../../size/) especificado dos valores das coordenadas X e Y do objeto [Point](../) especificado, respectivamente.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point | const [Point](../)\& | O ponto a ser traduzido |
| size | const [Size](../../size/)\& | O objeto [Size](../../size/) que especifica os valores a serem subtraídos dos valores das coordenadas do **point** |

### Valor de Retorno

Um novo objeto [Point](../) cujo valor da coordenada X é igual ao resultado da subtração do valor de largura de **size** do valor da coordenada X de **point** e o valor da coordenada Y é igual ao resultado da subtração do valor de altura de **size** do valor da coordenada Y de **point**.

## Veja Também

* Classe [Point](../)
* Classe [Size](../../size/)
* Espaço de nomes [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)