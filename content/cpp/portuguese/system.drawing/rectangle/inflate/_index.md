---
title: Inflate()
second_title: Referência da API Aspose.Slides para C++
description: Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados.
type: docs
weight: 261
url: /pt/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) método


Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | int | A quantidade pela qual a largura do retângulo deve ser aumentada em ambas as direções |
| height | int | A quantidade pela qual a altura do retângulo deve ser aumentada em ambas as direções |

## Rectangle::Inflate(const Size\&) método


Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores de largura e altura do objeto size especificado, respectivamente.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| size | const [Size](../../size/)\& | O objeto [Size](../../size/) que especifica as quantidades para aumentar a largura e a altura do retângulo |

## Rectangle::Inflate(const Rectangle\&, int, int) método


Aumenta a largura e a altura do retângulo representado pelo objeto especificado, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Um retângulo a ser inflado |
| x | int | A quantidade pela qual a largura do retângulo deve ser aumentada em ambas as direções |
| y | int | A quantidade pela qual a altura do retângulo deve ser aumentada em ambas as direções |

### Valor de Retorno

O objeto [Rectangle](../) que representa o retângulo ampliado

## Veja Também

* Classe [Rectangle](../)
* Classe [Size](../../size/)
* Namespace [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)