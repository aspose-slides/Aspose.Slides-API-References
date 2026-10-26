---
title: Rectangle class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo.
type: docs
url: /es/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Clase Rectangle

Almacena un conjunto de cuatro enteros que representan la ubicación y el tamaño de un rectángulo. Compatible con .NET `System.Drawing.Rectangle`.

El tipo Rectangle expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/es/aspose.slides/rectangle/__init__/#int-int-int-int) | Crea un rectángulo con la ubicación y el tamaño especificados. Los valores de punto flotante se truncan a enteros. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`x`](/slides/python-net/es/aspose.slides/rectangle/x/) | Obtiene la coordenada x de la esquina superior izquierda de este rectángulo.<br/>            Solo lectura **int**. |
| [`y`](/slides/python-net/es/aspose.slides/rectangle/y/) | Obtiene la coordenada y de la esquina superior izquierda de este rectángulo.<br/>            Solo lectura **int**. |
| [`width`](/slides/python-net/es/aspose.slides/rectangle/width/) | Obtiene el ancho de este rectángulo.<br/>            Solo lectura **int**. |
| [`height`](/slides/python-net/es/aspose.slides/rectangle/height/) | Obtiene la altura de este rectángulo.<br/>            Solo lectura **int**. |
| [`left`](/slides/python-net/es/aspose.slides/rectangle/left/) | Obtiene la coordenada x del borde izquierdo de este rectángulo. Equivalente a `x`.<br/>            Solo lectura **int**. |
| [`top`](/slides/python-net/es/aspose.slides/rectangle/top/) | Obtiene la coordenada y del borde superior de este rectángulo. Equivalente a `y`.<br/>            Solo lectura **int**. |
| [`right`](/slides/python-net/es/aspose.slides/rectangle/right/) | Obtiene la coordenada x que es la suma de `x` y `width` de este rectángulo.<br/>            Solo lectura **int**. |
| [`bottom`](/slides/python-net/es/aspose.slides/rectangle/bottom/) | Obtiene la coordenada y que es la suma de `y` y `height` de este rectángulo.<br/>            Solo lectura **int**. |
| [`is_empty`](/slides/python-net/es/aspose.slides/rectangle/is_empty/) | Especifica si todas las propiedades numéricas de este rectángulo tienen valores cero.<br/>            Solo lectura **bool**. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/es/aspose.slides/rectangle/contains/#int-int) | Determina si el punto especificado está contenido dentro de este rectángulo. |
| [`contains(self, point)`](/slides/python-net/es/aspose.slides/rectangle/contains/#point) | Determina si el punto especificado está contenido dentro de este rectángulo. |
| [`contains(self, rect)`](/slides/python-net/es/aspose.slides/rectangle/contains/#rectangle) | Determina si la región rectangular representada por `rect` está completamente contenida dentro de este rectángulo. |


### Observaciones

Los rectángulos se comparan por su ubicación y tamaño con `==` y pueden usarse como claves de diccionario o como miembros de conjuntos.


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)