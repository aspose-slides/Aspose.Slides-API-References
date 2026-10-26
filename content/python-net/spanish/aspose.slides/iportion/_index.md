---
title: IPortion class
second_title: Referencia de API de Aspose.Slides para Python via .NET
description: 
type: docs
url: /es/aspose.slides/iportion/
---
## IPortion clase

Representa una porción de texto dentro de un párrafo de texto.

El tipo IPortion expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`portion_format`](/slides/python-net/es/aspose.slides/iportion/portion_format/) | Devuelve el objeto de formato que contiene propiedades de formato establecidas explícitamente de la porción de texto sin herencia aplicada.<br/>            Solo lectura [`IPortionFormat`](/slides/python-net/es/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/es/aspose.slides/iportion/text/) | Obtiene o establece el texto plano de una porción.<br/>            Lectura/escritura **str**. |
| [`field`](/slides/python-net/es/aspose.slides/iportion/field/) | Devuelve un campo de esta porción.<br/>            Solo lectura [`IField`](/slides/python-net/es/aspose.slides/ifield). |
| [`slide`](/slides/python-net/es/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/iportion/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/es/aspose.slides/iportion/add_field/#ifieldtype) | Convierte esta porción al campo actualizado automáticamente. |
| [`add_field(self, internal_string)`](/slides/python-net/es/aspose.slides/iportion/add_field/#str) | Convierte esta porción al campo actualizado automáticamente. |
| [`remove_field(self)`](/slides/python-net/es/aspose.slides/iportion/remove_field/#) | Convierte esta porción de campo a la porción simple. |
| [`get_rect(self)`](/slides/python-net/es/aspose.slides/iportion/get_rect/#) | Obtiene las coordenadas del rectángulo que delimita la porción. El rectángulo incluye todas las líneas de<br/>             texto en la porción, incluidas las vacías. |
| [`get_coordinates(self)`](/slides/python-net/es/aspose.slides/iportion/get_coordinates/#) | Obtiene las coordenadas del comienzo de la porción. La coordenada X del punto representa el <br/>            comienzo de la porción desde el primer carácter, incluido el margen lateral izquierdo. La coordenada Y <br/>            incluye el margen superior. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)