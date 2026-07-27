---
title: Point()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um novo objeto Point e inicializa seus valores de coordenadas X e Y com 0.
type: docs
weight: 1
url: /pt/system.drawing/point/point/
---
## Point::Point() construtor


Constrói um novo objeto [Point](../) e inicializa os valores das coordenadas X e Y com 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) construtor


Constrói um novo objeto [Point](../) e o inicializa com os valores especificados.

```cpp
System::Drawing::Point::Point(int x, int y)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | int | O valor da coordenada X |
| y | int | O valor da coordenada Y |

## Point::Point(const Size\&) construtor


Constrói um novo objeto [Point](../) e inicializa os valores das coordenadas X e Y com os valores de largura e altura do objeto [SizeF](../../sizef/) especificado, respectivamente.

```cpp
System::Drawing::Point::Point(const Size &size)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Um objeto [SizeF](../../sizef/) cujos valores de largura e altura são usados para inicializar os valores das coordenadas X e Y do objeto [Point](../) que está sendo criado |

## Point::Point(int) construtor


Constrói um novo objeto [Point](../) e inicializa o valor da coordenada X com um valor formado pelos 16 bits mais altos do inteiro de 32 bits especificado e o valor da coordenada Y com um valor formado pelos 16 bits menos significativos do mesmo inteiro de 32 bits.

```cpp
System::Drawing::Point::Point(int dw)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dw | int | O valor inteiro de 32 bits cujos 16 bits mais altos especificam o valor da coordenada X e os 16 bits menos significativos especificam o valor da coordenada Y do objeto que está sendo criado |

## Ver Também

* Classe [Point](../)
* Classe [Size](../../size/)
* Namespace [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)