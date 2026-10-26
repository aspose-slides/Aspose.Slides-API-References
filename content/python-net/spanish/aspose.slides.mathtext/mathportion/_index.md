---
title: MathPortion class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathportion/
---
## MathPortion clase

Representa una porción con contexto matemático interno.

**Herencia:**[`MathPortion`](/slides/python-net/es/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/es/aspose.slides/portion)

El tipo MathPortion expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.mathtext/mathportion/__init__/#) | Inicializa una nueva instancia de la clase MathPortion. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`portion_format`](/slides/python-net/es/aspose.slides.mathtext/mathportion/portion_format/) | Devuelve el objeto de formato que contiene las propiedades de formato establecidas explícitamente de la porción de texto sin herencia aplicada.<br/>            Solo lectura [`IPortionFormat`](/slides/python-net/es/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/es/aspose.slides.mathtext/mathportion/text/) | Obtiene o establece el texto plano de una porción.<br/>            Lectura/escritura **str**. |
| [`field`](/slides/python-net/es/aspose.slides.mathtext/mathportion/field/) | Devuelve un campo de esta porción.<br/>            Solo lectura [`IField`](/slides/python-net/es/aspose.slides/ifield). |
| [`math_paragraph`](/slides/python-net/es/aspose.slides.mathtext/mathportion/math_paragraph/) | párrafo matemático |
| [`slide`](/slides/python-net/es/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.mathtext/mathportion/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/es/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | Convierte esta porción en el campo actualizado automáticamente. |
| [`add_field(self, internal_string)`](/slides/python-net/es/aspose.slides.mathtext/mathportion/add_field/#str) | Convierte esta porción en el campo actualizado automáticamente. |
| [`remove_field(self)`](/slides/python-net/es/aspose.slides.mathtext/mathportion/remove_field/#) | Convierte esta porción de campo en la porción simple. |
| [`get_rect(self)`](/slides/python-net/es/aspose.slides.mathtext/mathportion/get_rect/#) | Obtiene las coordenadas del rectángulo que delimita la porción. El rectángulo incluye todas las líneas de<br/>            texto en la porción, incluidas las vacías. |
| [`get_coordinates(self)`](/slides/python-net/es/aspose.slides.mathtext/mathportion/get_coordinates/#) | Obtiene las coordenadas del comienzo de la porción. La coordenada X del punto representa el <br/>            inicio de la porción desde el primer carácter, incluida la zona de desplazamiento lateral izquierda. La coordenada Y <br/>            incluye la zona de desplazamiento superior. |

### Ver también
* clase [`MathPortion`](/slides/python-net/es/aspose.slides.mathtext/mathportion)
* clase [`Portion`](/slides/python-net/es/aspose.slides/portion)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)