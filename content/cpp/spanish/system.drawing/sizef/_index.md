---
title: SizeF
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa un par de valores de coma flotante de precisión simple que representan el ancho y la altura de una imagen. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 287
url: /es/system.drawing/sizef/
---
## SizeF clase


Representa un par de valores de coma flotante de precisión simple que representan el ancho y la altura de una imagen. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class SizeF
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Devuelve un nuevo objeto [SizeF](./) que es la suma de los objetos [SizeF](./) especificados, es decir, cuyo valor de ancho es igual a la suma de los valores de ancho de los objetos especificados y cuyo valor de altura es igual a la suma de los valores de altura de los objetos especificados. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Determina si el objeto actual y el objeto especificado son iguales, es decir, representan el mismo par de valores de ancho y altura. |
| **float** [get_Height](./get_height/)() const | Devuelve el valor de altura representado por el objeto actual. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina si ambos valores de ancho y altura son iguales a 0. |
| **float** [get_Width](./get_width/)() const | Devuelve el valor de ancho representado por el objeto actual. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [operator PointF](./operator_pointf/)() const | Convierte el objeto actual a una instancia del objeto [Point](../point/) inicializando sus coordenadas X e Y con los valores de ancho y altura del objeto actual, respectivamente. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Añade los valores de ancho y altura del objeto [SizeF](./) especificado a los valores de ancho y altura del objeto [SizeF](./) actual, respectivamente. |
| void [set_Height](./set_height/)(**float**) | Establece el valor de altura representado por el objeto actual. |
| void [set_Width](./set_width/)(**float**) | Establece el valor de ancho representado por el objeto actual. |
| [SizeF](./sizef/)() | Construye un nuevo objeto [SizeF](./) e inicializa sus valores de ancho y altura con 0. |
| [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Construye un nuevo objeto [SizeF](./) e inicializa sus valores de ancho y altura con los valores de las coordenadas X e Y del punto especificado, respectivamente. |
| [SizeF](./sizef/)(**float**, **float**) | Construye un nuevo objeto [SizeF](./) e lo inicializa con el valor especificado. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Devuelve un nuevo objeto [SizeF](./) que es el resultado de la sustracción de **size2** a partir de **size1**, es decir, cuyo valor de ancho es el resultado de restar el valor de ancho de **size2** del valor de ancho de **size1** y cuyo valor de altura es el resultado de restar el valor de altura de **size2** del valor de altura de **size1**. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Convierte el objeto actual a una instancia del objeto [Point](../point/) inicializando sus coordenadas X e Y con los valores de ancho y altura del objeto actual, respectivamente. |
| [Size](../size/) [ToSize](./tosize/)() const | Construye un objeto [Size](../size/) a partir del objeto [SizeF](./) actual truncando los valores de ancho y altura del objeto [SizeF](./) al siguiente entero inferior. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Devuelve la representación en cadena del par de valores de ancho y altura representados por el objeto actual. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Una instancia vacía de la clase [SizeF](./) cuyos valores de ancho y altura son 0. |

## Ver también

* Espacio de nombres [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)