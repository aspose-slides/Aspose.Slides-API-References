---
title: Inflate()
second_title: Referência da API Aspose.Slides para C++
description: Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados.
type: docs
weight: 261
url: /pt/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) method


Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| width | **float** | A quantidade pela qual a largura do retângulo deve ser aumentada em ambas as direções |
| height | **float** | A quantidade pela qual a altura do retângulo deve ser aumentada em ambas as direções |

## RectangleF::Inflate(const SizeF\&) method


Aumenta a largura e a altura do retângulo representado pelo objeto atual, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores de largura e altura especificados pelo objeto de tamanho fornecido, respectivamente.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | O objeto [SizeF](../../sizef/) que especifica as quantidades para aumentar a largura e a altura do retângulo |

## RectangleF::Inflate(const RectangleF\&, float, float) method


Aumenta a largura e a altura do retângulo representado pelo objeto especificado, mantendo a localização do centro geométrico do retângulo. A largura e a altura são aumentadas em ambas as direções pelos valores especificados.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Um retângulo para inflar |
| x | **float** | A quantidade pela qual a largura do retângulo deve ser aumentada em ambas as direções |
| y | **float** | A quantidade pela qual a altura do retângulo deve ser aumentada em ambas as direções |

### Valor de Retorno

O objeto [RectangleF](../) que representa o retângulo ampliado

## Veja Também

* Classe [RectangleF](../)
* Classe [SizeF](../../sizef/)
* Namespace [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)