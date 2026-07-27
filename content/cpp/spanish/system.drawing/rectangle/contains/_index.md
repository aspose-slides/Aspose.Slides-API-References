---
title: Contains()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual.
type: docs
weight: 248
url: /es/system.drawing/rectangle/contains/
---
## Rectangle::Contains(int, int) const método

Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual.

```cpp
bool System::Drawing::Rectangle::Contains(int x, int y) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada X del punto a comprobar |
| y | int | La coordenada Y del punto a comprobar |

### Valor de retorno

True si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual, de lo contrario - false

## Rectangle::Contains(const Point&) const método

Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual.

```cpp
bool System::Drawing::Rectangle::Contains(const Point &point) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | const [Point](../../point/)\& | Un punto a comprobar |

### Valor de retorno

True si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual, de lo contrario - false

## Rectangle::Contains(const Rectangle&) const método

Determina si el rectángulo especificado se encuentra dentro del rectángulo representado por el objeto actual.

```cpp
bool System::Drawing::Rectangle::Contains(const Rectangle &rect) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Un rectángulo a comprobar |

### Valor de retorno

True si el rectángulo especificado se encuentra dentro del rectángulo representado por el objeto actual, de lo contrario - false

## Ver también

* Clase [Rectangle](../)
* Clase [Point](../../point/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)