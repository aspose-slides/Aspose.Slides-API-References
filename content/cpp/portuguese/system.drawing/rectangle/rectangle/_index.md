---
title: Rectangle()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância do objeto Rectangle que representa um retângulo com coordenadas X e Y e valores de largura e altura definidos como 0.
type: docs
weight: 1
url: /pt/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() construtor


Constrói uma nova instância do objeto [Rectangle](../) que representa um retângulo com coordenadas X e Y e valores de largura e altura definidos como 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) construtor


Constrói uma nova instância do objeto [Rectangle](../) que representa um retângulo com as coordenadas especificadas do seu canto superior esquerdo e largura e altura.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | int | Um valor da coordenada X do canto superior esquerdo do retângulo |
| y | int | Um valor da coordenada Y do canto superior esquerdo do retângulo |
| width | int | A largura do retângulo |
| height | int | A altura do retângulo |

## Rectangle::Rectangle(const Point\&, const Size\&) construtor


Constrói uma nova instância do objeto [Rectangle](../) que representa um retângulo com as coordenadas do seu canto superior esquerdo especificadas como uma instância da classe [Point](../../point/) e sua largura e altura como uma instância da classe [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Especifica a localização do canto superior esquerdo do retângulo |
| size | const [Size](../../size/)\& | Especifica a largura e a altura do retângulo |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) construtor


Constrói uma nova instância do objeto [Rectangle](../) que representa o retângulo equivalente ao especificado.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Uma instância da classe **System::Windows::Forms::Screen::Rectangle_** que especifica a posição e o tamanho do retângulo a ser representado pelo objeto que está sendo construído |

## Veja Também

* Classe [Rectangle](../)
* Classe [Point](../../point/)
* Classe [Size](../../size/)
* Espaço de nomes [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)