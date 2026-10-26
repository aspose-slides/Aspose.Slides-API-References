---
title: Point
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un par de coordenadas enteras X e Y de un punto en un plano bidimensional. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 209
url: /es/system.drawing/point/
---
## Clase Point

Representa un par de coordenadas enteras X e Y de un punto en un plano bidimensional. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class Point
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Agrega los valores de ancho y alto del objeto [Size](../size/) especificado a los valores de las coordenadas X y Y del objeto [Point](./) especificado correspondientemente. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Construye un objeto [Point](./) a partir del objeto [PointF](../pointf/) especificado redondeando los valores de las coordenadas X y Y del objeto [PointF](../pointf/) al siguiente entero mayor. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Determina si el objeto actual y el objeto especificado son iguales, es decir, representan el mismo par de valores de coordenadas X y Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina si los valores de las coordenadas X y Y son iguales a 0. |
| int [get_X](./get_x/)() const | Devuelve el valor de la coordenada X representado por el objeto actual. |
| int [get_Y](./get_y/)() const | Devuelve el valor de la coordenada Y representado por el objeto actual. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| size_t [getStdHash](./getstdhash/)() const | Devuelve un valor hash para el objeto actual. |
| **bool** [IsNull](./isnull/)() const | Siempre devuelve false. |
| void [Offset](./offset/)(int, int) | Desplaza el valor de las coordenadas X y Y representado por el objeto actual por los valores especificados. |
| void [Offset](./offset/)([Point](./)) | Desplaza las coordenadas X y Y representadas por el objeto actual por los valores de las coordenadas X y Y representadas por el objeto [Point](./) especificado correspondientemente. |
| [operator PointF](./operator_pointf/)() const | Construye una instancia del objeto [PointF](../pointf/) y la inicializa con los valores de coordenadas X y Y del objeto [Point](./) actual. |
| [operator Size](./operator_size/)() const | Construye una instancia del objeto [Size](../size/) y inicializa sus valores de ancho y alto con los valores de coordenadas X y Y representados por el objeto actual correspondientemente. |
| [Point](./point/)() | Construye un nuevo objeto [Point](./) e inicializa sus valores de coordenadas X y Y con 0. |
| [Point](./point/)(int, int) | Construye un nuevo objeto [Point](./) e lo inicializa con los valores especificados. |
| [Point](./point/)(const [Size](../size/)\&) | Construye un nuevo objeto [Point](./) e inicializa sus valores de coordenadas X y Y con los valores de ancho y alto del objeto [SizeF](../sizef/) especificado correspondientemente. |
| [Point](./point/)(int) | Construye un nuevo objeto [Point](./) e inicializa su valor de coordenada X con un valor formado por los 16 bits altos del entero de 32 bits especificado y su valor de coordenada Y con un valor formado por los 16 bits bajos del mismo entero de 32 bits especificado. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Construye un objeto [Point](./) a partir del objeto [PointF](../pointf/) especificado redondeando los valores de las coordenadas X y Y del objeto [PointF](../pointf/) al entero más cercano. |
| void [set_X](./set_x/)(int) | Establece el valor de la coordenada X representado por el objeto actual. |
| void [set_Y](./set_y/)(int) | Establece el valor de la coordenada Y representado por el objeto actual. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Resta los valores de ancho y alto del objeto [Size](../size/) especificado de los valores de coordenadas X y Y del objeto [Point](./) especificado correspondientemente. |
| [String](../../system/string/) [ToString](./tostring/)() const | Devuelve la representación en cadena del par de valores de coordenadas X y Y representados por el objeto actual. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Construye un objeto [Point](./) a partir del objeto [PointF](../pointf/) especificado truncando los valores de coordenadas X y Y del objeto [PointF](../pointf/) al siguiente entero inferior. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Una instancia vacía de la clase [Point](./) cuyas coordenadas X y Y son 0. |

## Ver también

* Espacio de nombres [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)