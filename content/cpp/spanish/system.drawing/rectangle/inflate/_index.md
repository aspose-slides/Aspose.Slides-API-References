---
title: Inflate()
second_title: Referencia de API de Aspose.Slides para C++
description: Aumenta el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores especificados.
type: docs
weight: 261
url: /es/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) método

Aumenta el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores especificados.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | La cantidad en la que se debe incrementar el ancho del rectángulo en ambas direcciones |
| height | int | La cantidad en la que se debe incrementar la altura del rectángulo en ambas direcciones |

## Rectangle::Inflate(const Size\&) método

Aumenta el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores de ancho y altura especificados por el objeto size indicado de forma correspondiente.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | const [Size](../../size/)\& | El objeto [Size](../../size/) que especifica las cantidades por las que se aumentarán el ancho y la altura del rectángulo |

## Rectangle::Inflate(const Rectangle\&, int, int) método

Aumenta el ancho y la altura del rectángulo representado por el objeto especificado, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores especificados.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Un rectángulo para inflar |
| x | int | La cantidad en la que se debe incrementar el ancho del rectángulo en ambas direcciones |
| y | int | La cantidad en la que se debe incrementar la altura del rectángulo en ambas direcciones |

### Valor devuelto

El objeto [Rectangle](../) que representa el rectángulo ampliado

## Ver también

* Clase [Rectangle](../)
* Clase [Size](../../size/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)