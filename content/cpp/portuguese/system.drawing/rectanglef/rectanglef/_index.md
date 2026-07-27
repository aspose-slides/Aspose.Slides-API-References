---
title: RectangleF()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância do objeto RectangleF que representa um retângulo com coordenadas X e Y e valores de largura e altura definidos como 0.
type: docs
weight: 1
url: /pt/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() construtor


Constrói uma nova instância do objeto [RectangleF](../) que representa um retângulo com coordenadas X e Y e valores de largura e altura definidos como 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) construtor


Constrói uma nova instância do objeto [RectangleF](../) que representa um retângulo com as coordenadas especificadas do canto superior esquerdo e largura e altura.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | Um valor da coordenada X do canto superior esquerdo do retângulo |
| y | **float** | Um valor da coordenada Y do canto superior esquerdo do retângulo |
| width | **float** | A largura do retângulo |
| height | **float** | A altura do retângulo |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) construtor


Constrói uma nova instância do objeto [RectangleF](../) que representa um retângulo com as coordenadas do canto superior esquerdo especificadas como uma instância da classe [PointF](../../pointf/) e sua largura e altura como uma instância da classe [SizeF](../../sizef/).

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Especifica a localização do canto superior esquerdo do retângulo |
| size | const [SizeF](../../sizef/)\& | Especifica a largura e a altura do retângulo |

## RectangleF::RectangleF(const Rectangle\&) construtor


Constrói uma nova instância do objeto [RectangleF](../) que representa o retângulo equivalente ao especificado.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Uma instância da classe [Rectangle](../../rectangle/) que especifica a posição e o tamanho do retângulo a ser representado pelo objeto em construção |

## Ver Também

* Classe [RectangleF](../)
* Classe [PointF](../../pointf/)
* Classe [SizeF](../../sizef/)
* Classe [Rectangle](../../rectangle/)
* Espaço de nomes [System::Drawing](../../)
* Library [Aspose.Slides](../../../)