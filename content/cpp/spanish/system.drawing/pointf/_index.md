---
title: PointF
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un par de coordenadas X e Y de punto en un plano bidimensional de precisión simple de punto flotante. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca utilice la clase System::SmartPtr para administrar objetos de este tipo."
type: docs
weight: 222
url: /es/system.drawing/pointf/
---
## PointF clase


Representa un par de coordenadas X e Y de punto en un plano bidimensional de precisión simple de punto flotante. Este tipo debe asignarse en la pila y pasarse a las funciones por valor o por referencia. Nunca utilice la clase [System::SmartPtr](../../system/smartptr/) para administrar objetos de este tipo.

```cpp
class PointF
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Añade los valores de ancho y alto del objeto [SizeF](../sizef/) especificado a los valores de coordenadas X y Y del objeto [PointF](./) especificado correspondientemente. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Añade los valores de ancho y alto del objeto [Size](../size/) especificado a los valores de coordenadas X y Y del objeto [PointF](./) especificado correspondientemente. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Determina si el objeto actual y el objeto especificado son iguales, es decir, representan el mismo par de valores de coordenadas X y Y. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determina si ambos valores de coordenadas X y Y son iguales a 0. |
| **float** [get_X](./get_x/)() const | Devuelve el valor de la coordenada X representada por el objeto actual. |
| **float** [get_Y](./get_y/)() const | Devuelve el valor de la coordenada Y representada por el objeto actual. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| **bool** [IsNull](./isnull/)() const | Siempre devuelve false. |
| explicit  [operator bool](./operator_bool/)() | Siempre devuelve true. |
|  [PointF](./pointf/)() | Construye un nuevo objeto [PointF](./) e inicializa sus valores de coordenadas X y Y con 0. |
|  [PointF](./pointf/)(**float**, **float**) | Construye un nuevo objeto [PointF](./) y lo inicializa con los valores especificados. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Construye un nuevo objeto [PointF](./) e inicializa sus valores de coordenadas X y Y con los valores de ancho y alto del objeto [SizeF](../sizef/) especificado correspondientemente. |
| void [set_X](./set_x/)(**float**) | Establece el valor de la coordenada X representada por el objeto actual. |
| void [set_Y](./set_y/)(**float**) | Establece el valor de la coordenada Y representada por el objeto actual. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Resta los valores de ancho y alto del objeto [SizeF](../sizef/) especificado de los valores de coordenadas X y Y del objeto [PointF](./) especificado correspondientemente. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Resta los valores de ancho y alto del objeto [Size](../size/) especificado de los valores de coordenadas X y Y del objeto [PointF](./) especificado correspondientemente. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Devuelve la representación en cadena del par de valores de coordenadas X y Y representado por el objeto actual. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Una instancia vacía de la clase [PointF](./) cuyos valores de coordenadas X y Y son 0. |

## Ver también

* Espacio de nombres [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)