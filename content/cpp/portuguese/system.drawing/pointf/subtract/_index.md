---
title: Subtract()
second_title: Referência da API Aspose.Slides para C++
description: Subtrai os valores de largura e altura do objeto SizeF especificado dos valores das coordenadas X e Y do objeto PointF especificado, respectivamente.
type: docs
weight: 157
url: /pt/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) método


Subtrai os valores de largura e altura do objeto [SizeF](../../sizef/) especificado dos valores das coordenadas X e Y do objeto [PointF](../) especificado, respectivamente.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point | const [PointF](../)\& | O ponto a ser traduzido |
| size | const [SizeF](../../sizef/)\& | O objeto [SizeF](../../sizef/) que especifica os valores a serem subtraídos dos valores das coordenadas do **point** |

### Valor de Retorno

Um novo objeto [PointF](../) cujo valor da coordenada X é igual ao resultado da subtração do valor de largura de **size** do valor da coordenada X de **point** e cujo valor da coordenada Y é igual ao resultado da subtração do valor de altura de **size** do valor da coordenada Y de **point**.

## PointF::Subtract(const PointF\&, const Size\&) método


Subtrai os valores de largura e altura do objeto [Size](../../size/) especificado dos valores das coordenadas X e Y do objeto [PointF](../) especificado, respectivamente.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| point | const [PointF](../)\& | O ponto a ser traduzido |
| size | const [Size](../../size/)\& | O objeto [Size](../../size/) que especifica os valores a serem subtraídos dos valores das coordenadas do **point** |

### Valor de Retorno

Um novo objeto [PointF](../) cujo valor da coordenada X é igual ao resultado da subtração do valor de largura de **size** do valor da coordenada X de **point** e cujo valor da coordenada Y é igual ao resultado da subtração do valor de altura de **size** do valor da coordenada Y de **point**.

## Veja Também

* Classe [PointF](../)
* Classe [SizeF](../../sizef/)
* Classe [Size](../../size/)
* Espaço de nomes [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)