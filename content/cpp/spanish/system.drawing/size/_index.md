---
title: Size
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un par de valores enteros que representan el ancho y la altura de una imagen. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 274
url: /es/system.drawing/size/
---
## Clase Size

Representa un par de valores enteros que representan el ancho y la altura de una imagen. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class Size
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Devuelve un nuevo objeto [Size](./) que es la suma del objeto [Size](./) especificado, es decir, cuyo valor de ancho es igual a la suma de los valores de ancho de los objetos especificados y cuyo valor de alto es igual a la suma de los valores de alto de los objetos especificados. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Construye un objeto [Size](./) a partir del objeto [SizeF](../sizef/) especificado redondeando los valores de ancho y alto del objeto [SizeF](../sizef/) al siguiente entero superior. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Determina si el objeto actual y el objeto especificado son iguales, es decir, representan el mismo par de valores de ancho y alto. |
| int [get_Height](./get_height/)() const | Devuelve el valor del alto representado por el objeto actual. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina si los valores de ancho y alto son iguales a 0. |
| int [get_Width](./get_width/)() const | Devuelve el valor del ancho representado por el objeto actual. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
|  [operator Point](./operator_point/)() const | Construye una instancia del objeto [Point](../point/) e inicializa sus coordenadas X e Y con los valores de ancho y alto del objeto actual, respectivamente. |
|  [operator SizeF](./operator_sizef/)() const | Construye una instancia del objeto [SizeF](../sizef/) e inicialízala con los valores de ancho y alto del objeto [Size](./) actual. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Construye un objeto [Size](./) a partir del objeto [SizeF](../sizef/) especificado redondeando los valores de ancho y alto del objeto [SizeF](../sizef/) al entero más cercano. |
| void [set_Height](./set_height/)(int) | Establece el valor del alto representado por el objeto actual. |
| void [set_Width](./set_width/)(int) | Establece el valor del ancho representado por el objeto actual. |
|  [Size](./size/)() | Construye un nuevo objeto [Size](./) e inicializa sus valores de ancho y alto con 0. |
|  [Size](./size/)(const [Point](../point/)\&) | Construye un nuevo objeto [Size](./) e inicializa sus valores de ancho y alto con los valores de las coordenadas X e Y del punto especificado, respectivamente. |
|  [Size](./size/)(int, int) | Construye un nuevo objeto [Size](./) e lo inicializa con el valor especificado. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Devuelve un nuevo objeto [Size](./) que es el resultado de la sustracción de **size2** de **size1**, es decir, cuyo valor de ancho es el resultado de restar el valor de ancho de **size2** al valor de ancho de **size1**, y cuyo valor de alto es el resultado de restar el valor de alto de **size2** al valor de alto de **size1**. |
| [String](../../system/string/) [ToString](./tostring/)() const | Devuelve la representación en cadena del par de valores de ancho y alto representado por el objeto actual. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Construye un objeto [Size](./) a partir del objeto [SizeF](../sizef/) especificado truncando los valores de ancho y alto del objeto [SizeF](../sizef/) al entero inferior más cercano. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Una instancia vacía de la clase [Size](./) cuyos valores de ancho y alto son 0. |

## Ver también

* Espacio de nombres [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)