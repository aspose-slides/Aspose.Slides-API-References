---
title: RectangleF class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo.
type: docs
url: /es/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## Clase RectangleF

Almacena un conjunto de cuatro números de punto flotante que representan la ubicación y el tamaño de un rectángulo. Compatible con .NET `System.Drawing.RectangleF`.

**Herencia:**[`RectangleF`](/slides/python-net/es/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/es/aspose.slides/rectangle)

El tipo RectangleF expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/es/aspose.slides/rectanglef/__init__/#float-float-float-float) | Crea un rectángulo con la ubicación y el tamaño especificados. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`x`](/slides/python-net/es/aspose.slides/rectanglef/x/) | Obtiene la coordenada x de la esquina superior izquierda de este rectángulo.<br/>            Solo lectura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/rectanglef/y/) | Obtiene la coordenada y de la esquina superior izquierda de este rectángulo.<br/>            Solo lectura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/rectanglef/width/) | Obtiene el ancho de este rectángulo.<br/>            Solo lectura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/rectanglef/height/) | Obtiene la altura de este rectángulo.<br/>            Solo lectura **float**. |
| [`left`](/slides/python-net/es/aspose.slides/rectanglef/left/) | Obtiene la coordenada x del borde izquierdo de este rectángulo. Igual a `x`.<br/>            Solo lectura **float**. |
| [`top`](/slides/python-net/es/aspose.slides/rectanglef/top/) | Obtiene la coordenada y del borde superior de este rectángulo. Igual a `y`.<br/>            Solo lectura **float**. |
| [`right`](/slides/python-net/es/aspose.slides/rectanglef/right/) | Obtiene la coordenada x que es la suma de `x` y `width` de este rectángulo.<br/>            Solo lectura **float**. |
| [`bottom`](/slides/python-net/es/aspose.slides/rectanglef/bottom/) | Obtiene la coordenada y que es la suma de `y` y `height` de este rectángulo.<br/>            Solo lectura **float**. |
| [`is_empty`](/slides/python-net/es/aspose.slides/rectanglef/is_empty/) | Especifica si todas las propiedades numéricas de este rectángulo tienen valores cero.<br/>            Solo lectura **bool**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/es/aspose.slides/rectanglef/contains/#float-float) | Determina si el punto especificado está contenido dentro de este rectángulo. |
| [`contains(self, point)`](/slides/python-net/es/aspose.slides/rectanglef/contains/#pointf) | Determina si el punto especificado está contenido dentro de este rectángulo. |
| [`contains(self, rect)`](/slides/python-net/es/aspose.slides/rectanglef/contains/#rectanglef) | Determina si la región rectangular representada por `rect` está totalmente contenida dentro de este rectángulo. |


### Comentarios

Los rectángulos se comparan por su ubicación y tamaño con `==` y pueden usarse como claves de diccionario o miembros de conjunto.


### Ver también
* clase [`Rectangle`](/slides/python-net/es/aspose.slides/rectangle)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)