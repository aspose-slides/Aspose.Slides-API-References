---
title: Portion class
second_title: Aspose.Slides para Python mediante .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/portion/
---
## Clase Portion

Representa una porción de texto dentro de un párrafo de texto.

El tipo Portion expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides/portion/__init__/#) | Inicializa una nueva instancia de la clase Portion. |
| [`__init__(self, str)`](/slides/python-net/es/aspose.slides/portion/__init__/#str) | Inicializa una nueva instancia de la clase Portion. |
| [`__init__(self, portion)`](/slides/python-net/es/aspose.slides/portion/__init__/#portion) | Inicializa una nueva instancia de la clase Portion. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`portion_format`](/slides/python-net/es/aspose.slides/portion/portion_format/) | Devuelve el objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin aplicar herencia.<br/>            Solo lectura [`IPortionFormat`](/slides/python-net/es/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/es/aspose.slides/portion/text/) | Obtiene o establece el texto sin formato de una porción.<br/>            Lectura/escritura **str**. |
| [`field`](/slides/python-net/es/aspose.slides/portion/field/) | Devuelve un campo de esta porción.<br/>            Solo lectura [`IField`](/slides/python-net/es/aspose.slides/ifield). |
| [`slide`](/slides/python-net/es/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/portion/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/es/aspose.slides/portion/add_field/#ifieldtype) | Convierte esta porción en el campo actualizado automáticamente. |
| [`add_field(self, internal_string)`](/slides/python-net/es/aspose.slides/portion/add_field/#str) | Convierte esta porción en el campo actualizado automáticamente. |
| [`remove_field(self)`](/slides/python-net/es/aspose.slides/portion/remove_field/#) | Convierte esta porción de campo en la porción simple. |
| [`get_rect(self)`](/slides/python-net/es/aspose.slides/portion/get_rect/#) | Obtiene las coordenadas del rectángulo que delimita la porción. El rectángulo incluye todas las líneas de<br/>             texto en la porción, incluidas las vacías. |
| [`get_coordinates(self)`](/slides/python-net/es/aspose.slides/portion/get_coordinates/#) | Obtiene las coordenadas del inicio de la porción. La coordenada X del punto representa el inicio de la porción desde el primer carácter, incluyendo la dactilografía del lado izquierdo. La coordenada Y incluye la dactilografía del lado superior. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)