---
title: Rectangle
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un área rectangular de una imagen definida por coordenadas enteras X y Y de su esquina superior izquierda y su anchura y altura. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 235
url: /es/system.drawing/rectangle/
---
## Rectangle clase


Representa un área rectangular de una imagen definida por coordenadas enteras X y Y de su esquina superior izquierda y su anchura y altura. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use [System::SmartPtr](../../system/smartptr/) class para gestionar objetos de este tipo.

```cpp
class Rectangle
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Construye un objeto [Rectangle](./) a partir del objeto [RectangleF](../rectanglef/) especificado redondeando los valores de ubicación y tamaño del objeto [RectangleF](../rectanglef/) a los siguientes valores enteros superiores. |
| **bool** [Contains](./contains/)(int, int) const | Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Determina si el rectángulo especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Determina si los rectángulos representados por el objeto actual y el objeto especificado son idénticos. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Construye un nuevo objeto [Rectangle](./) que representa un rectángulo con las ubicaciones de los bordes especificadas. |
| int [get_Bottom](./get_bottom/)() const | Devuelve la coordenada y del borde inferior del rectángulo representado por el objeto actual. |
| int [get_Height](./get_height/)() const | Devuelve la altura del rectángulo representado por el objeto actual. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina si las coordenadas X y Y de la esquina superior izquierda del rectángulo representado por el objeto actual, así como su anchura y altura, tienen valores de 0. |
| int [get_Left](./get_left/)() const | Devuelve la coordenada X del borde izquierdo del rectángulo representado por el objeto actual. |
| [Point](../point/) [get_Location](./get_location/)() const | Devuelve una instancia de la clase [Point](../point/) que especifica la ubicación de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| int [get_Right](./get_right/)() const | Devuelve la coordenada X del borde derecho del rectángulo representado por el objeto actual. |
| [Size](../size/) [get_Size](./get_size/)() const | Devuelve una instancia de la clase [Size](../size/) que especifica la anchura y altura del rectángulo representado por el objeto actual. |
| int [get_Top](./get_top/)() const | Devuelve la coordenada Y del borde superior del rectángulo representado por el objeto actual. |
| int [get_Width](./get_width/)() const | Devuelve la anchura del rectángulo representado por el objeto actual. |
| int [get_X](./get_x/)() const | Devuelve la coordenada X de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| int [get_Y](./get_y/)() const | Devuelve la coordenada Y de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash del objeto actual. |
| void [Inflate](./inflate/)(int, int) | Aumenta la anchura y altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. La anchura y altura se incrementan en ambas direcciones por las cantidades especificadas. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Aumenta la anchura y altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. La anchura y altura se incrementan en ambas direcciones por los valores de anchura y altura del objeto de tamaño especificado correspondientes. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Aumenta la anchura y altura del rectángulo representado por el objeto especificado, manteniendo la ubicación del centro geométrico del rectángulo. La anchura y altura se incrementan en ambas direcciones por las cantidades especificadas. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Reemplaza el rectángulo representado por el objeto actual con el rectángulo que resulta de su intersección con el rectángulo representado por el objeto especificado. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Devuelve un rectángulo que es el resultado de la intersección de los rectángulos especificados. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Determina si los rectángulos representados por el objeto actual y el objeto especificado se intersectan. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Desplaza la posición del rectángulo representado por el objeto actual por los valores especificados. |
| void [Offset](./offset/)(int, int) | Desplaza la posición del rectángulo representado por el objeto actual por los valores especificados. |
|  [operator RectangleF](./operator_rectanglef/)() const | Devuelve un objeto [RectangleF](../rectanglef/) que representa un rectángulo equivalente al rectángulo representado por el objeto actual. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Siempre devuelve true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Siempre devuelve false. |
|  [Rectangle](./rectangle/)() | Construye una nueva instancia del objeto [Rectangle](./) que representa un rectángulo con coordenadas X y Y y valores de anchura y altura establecidos a 0. |
|  [Rectangle](./rectangle/)(int, int, int, int) | Construye una nueva instancia del objeto [Rectangle](./) que representa un rectángulo con las coordenadas especificadas de su esquina superior izquierda y su anchura y altura. |
|  [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Construye una nueva instancia del objeto [Rectangle](./) que representa un rectángulo con las coordenadas de su esquina superior izquierda especificadas como una instancia de la clase [Point](../point/) y su anchura y altura como una instancia de la clase [Size](../size/). |
|  [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Construye una nueva instancia del objeto [Rectangle](./) que representa el rectángulo equivalente al especificado. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Construye un objeto [Rectangle](./) a partir del objeto [RectangleF](../rectanglef/) especificado redondeando los valores de ubicación y tamaño del objeto [RectangleF](../rectanglef/) al entero más cercano. |
| void [set_Height](./set_height/)(int) | Establece la altura del rectángulo representado por el objeto actual. |
| void [set_Location](./set_location/)([Point](../point/)) | Establece la ubicación de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| void [set_Size](./set_size/)([Size](../size/)) | Establece la anchura y altura del rectángulo representado por el objeto actual. |
| void [set_Width](./set_width/)(int) | Establece la anchura del rectángulo representado por el objeto actual. |
| void [set_X](./set_x/)(int) | Establece la coordenada X de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| void [set_Y](./set_y/)(int) | Establece la coordenada Y de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [String](../../system/string/) [ToString](./tostring/)() const | Devuelve la representación en cadena del objeto actual. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Construye un objeto [Rectangle](./) a partir del objeto [RectangleF](../rectanglef/) especificado truncando los valores de ubicación y tamaño del objeto [RectangleF](../rectanglef/) al siguiente entero inferior. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Devuelve un rectángulo que es el resultado de la unión de los rectángulos especificados. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Un rectángulo vacío, es decir, un rectángulo cuyas valores de ubicación y tamaño son cero. |

## Véase también

* Espacio de nombres [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)