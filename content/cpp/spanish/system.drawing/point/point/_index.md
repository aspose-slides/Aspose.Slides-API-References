---
title: Point()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye un nuevo objeto Point e inicializa sus valores de coordenadas X y Y con 0.
type: docs
weight: 1
url: /es/system.drawing/point/point/
---
## Point::Point() constructor

Construye un nuevo objeto [Point](../) y inicializa sus valores de coordenadas X y Y con 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) constructor

Construye un nuevo objeto [Point](../) y lo inicializa con los valores especificados.

```cpp
System::Drawing::Point::Point(int x, int y)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | El valor de la coordenada X |
| y | int | El valor de la coordenada Y |

## Point::Point(const Size\&) constructor

Construye un nuevo objeto [Point](../) e inicializa sus valores de coordenadas X y Y con los valores de ancho y alto del objeto [SizeF](../../sizef/) especificado, respectivamente.

```cpp
System::Drawing::Point::Point(const Size &size)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | const [Size](../../size/)\& | Un objeto [SizeF](../../sizef/) cuyos valores de ancho y alto se utilizan para inicializar los valores de coordenadas X y Y del objeto [Point](../) que se está creando |

## Point::Point(int) constructor

Construye un nuevo objeto [Point](../) e inicializa su valor de coordenada X con un valor formado por los 16 bits más altos del entero de 32 bits especificado y su valor de coordenada Y con un valor formado por los 16 bits más bajos del entero de 32 bits especificado.

```cpp
System::Drawing::Point::Point(int dw)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dw | int | El valor entero de 32 bits cuyos 16 bits más altos especifican el valor de la coordenada X y cuyos 16 bits más bajos especifican el valor de la coordenada Y del objeto que se está creando |

## Ver también

* Clase [Point](../)
* Clase [Size](../../size/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)