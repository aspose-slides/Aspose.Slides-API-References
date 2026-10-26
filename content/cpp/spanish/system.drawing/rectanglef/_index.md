---
title: RectangleF
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un área rectangular de una imagen definida como coordenadas X y Y de punto flotante de precisión simple de su esquina superior izquierda y su ancho y alto. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca utilice la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 248
url: /es/system.drawing/rectanglef/
---
## RectangleF clase

Representa un área rectangular de una imagen definida por coordenadas X y Y de precisión simple de punto flotante de su esquina superior izquierda y su ancho y alto. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca utilice la clase [System::SmartPtr](../../system/smartptr/) para gestionar objetos de este tipo.

```cpp
class RectangleF
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Determina si el punto especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Determina si el rectángulo especificado se encuentra dentro del rectángulo representado por el objeto actual. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Determina si los rectángulos representados por el objeto actual y el objeto especificado son idénticos. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Construye un nuevo objeto [RectangleF](./) que representa un rectángulo con las ubicaciones de borde especificadas. |
| **float** [get_Bottom](./get_bottom/)() const | Devuelve la coordenada y del borde inferior del rectángulo representado por el objeto actual. |
| **float** [get_Height](./get_height/)() const | Devuelve la altura del rectángulo representado por el objeto actual. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina si las coordenadas X y Y de la esquina superior izquierda del rectángulo representado por el objeto actual, así como su ancho y altura, tienen valores de 0. |
| **float** [get_Left](./get_left/)() const | Devuelve la coordenada X del borde izquierdo del rectángulo representado por el objeto actual. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Devuelve una instancia de la clase [PointF](../pointf/) que especifica la ubicación de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| **float** [get_Right](./get_right/)() const | Devuelve la coordenada X del borde derecho del rectángulo representado por el objeto actual. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Devuelve una instancia de la clase [SizeF](../sizef/) que especifica el ancho y la altura del rectángulo representado por el objeto actual. |
| **float** [get_Top](./get_top/)() const | Devuelve la coordenada Y del borde superior del rectángulo representado por el objeto actual. |
| **float** [get_Width](./get_width/)() const | Devuelve el ancho del rectángulo representado por el objeto actual. |
| **float** [get_X](./get_x/)() const | Devuelve la coordenada X de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| **float** [get_Y](./get_y/)() const | Devuelve la coordenada Y de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash del objeto actual. |
| void [Inflate](./inflate/)(**float**, **float**) | Incrementa el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores especificados. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Incrementa el ancho y la altura del rectángulo representado por el objeto actual, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones según los valores de ancho y altura del objeto de tamaño especificado. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Incrementa el ancho y la altura del rectángulo representado por el objeto especificado, manteniendo la ubicación del centro geométrico del rectángulo. El ancho y la altura se incrementan en ambas direcciones por los valores especificados. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Reemplaza el rectángulo representado por el objeto actual con el rectángulo que resulta de su intersección con el rectángulo representado por el objeto especificado. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Devuelve un rectángulo que es el resultado de la intersección de los rectángulos especificados. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Determina si los rectángulos representados por el objeto actual y el objeto especificado se intersectan. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Desplaza la posición del rectángulo representado por el objeto actual por los valores especificados. |
| void [Offset](./offset/)(**float**, **float**) | Desplaza la posición del rectángulo representado por el objeto actual por los valores especificados. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Siempre devuelve true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Siempre devuelve false. |
| [RectangleF](./rectanglef/)() | Construye una nueva instancia del objeto [RectangleF](./) que representa un rectángulo con coordenadas X y Y y valores de ancho y altura establecidos en 0. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Construye una nueva instancia del objeto [RectangleF](./) que representa un rectángulo con las coordenadas especificadas de su esquina superior izquierda y su ancho y altura. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Construye una nueva instancia del objeto [RectangleF](./) que representa un rectángulo con las coordenadas de su esquina superior izquierda especificadas como una instancia de la clase [PointF](../pointf/) y su ancho y altura como una instancia de la clase [SizeF](../sizef/). |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Construye una nueva instancia del objeto [RectangleF](./) que representa el rectángulo equivalente al especificado. |
| void [set_Height](./set_height/)(**float**) | Establece la altura del rectángulo representado por el objeto actual. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Establece la ubicación de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Establece el ancho y la altura del rectángulo representado por el objeto actual. |
| void [set_Width](./set_width/)(**float**) | Establece el ancho del rectángulo representado por el objeto actual. |
| void [set_X](./set_x/)(**float**) | Establece la coordenada X de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| void [set_Y](./set_y/)(**float**) | Establece la coordenada Y de la esquina superior izquierda del rectángulo representado por el objeto actual. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Devuelve la representación en forma de cadena del objeto actual. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Devuelve un rectángulo que es el resultado de la unión de los rectángulos especificados. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Un rectángulo vacío, es decir, un rectángulo cuyas coordenadas de ubicación y tamaño son cero. |

## Ver también

* Espacio de nombres [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)