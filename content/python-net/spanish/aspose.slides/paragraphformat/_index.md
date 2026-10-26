---
title: ParagraphFormat class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/paragraphformat/
---
## ParagraphFormat clase

Esta clase contiene las propiedades de formato de párrafo. A diferencia de [`IParagraphFormatEffectiveData`](/slides/python-net/es/aspose.slides/iparagraphformateffectivedata), todas las propiedades de esta clase son editables.

**Inheritance:**[`ParagraphFormat`](/slides/python-net/es/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)

El tipo ParagraphFormat expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides/paragraphformat/__init__/#) | Inicializa una nueva instancia de la clase [`ParagraphFormat`](/slides/python-net/es/aspose.slides/paragraphformat). |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`alignment`](/slides/python-net/es/aspose.slides/paragraphformat/alignment/) | Devuelve o establece la alineación del texto en un párrafo sin herencia.<br/>            Lectura/escritura [`TextAlignment`](/slides/python-net/es/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/es/aspose.slides/paragraphformat/space_within/) | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo significa porcentaje, uno negativo - tamaño en puntos. No se aplica herencia.<br/>            Lectura/escritura **float**. |
| [`space_before`](/slides/python-net/es/aspose.slides/paragraphformat/space_before/) | Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia.<br/>            Un valor positivo especifica el porcentaje del tamaño de fuente que debe ocupar el espacio en blanco.<br/>            Un valor negativo especifica el tamaño del espacio en blanco en puntos.<br/>            Lectura/escritura **float**. |
| [`space_after`](/slides/python-net/es/aspose.slides/paragraphformat/space_after/) | Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia.<br/>            Un valor positivo especifica el porcentaje del tamaño de fuente que debe ocupar el espacio en blanco.<br/>            Un valor negativo especifica el tamaño del espacio en blanco en puntos.<br/>            Lectura/escritura **float**. |
| [`east_asian_line_break`](/slides/python-net/es/aspose.slides/paragraphformat/east_asian_line_break/) | Determina si se usa el salto de línea de Asia Oriental en un párrafo. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/es/aspose.slides/paragraphformat/right_to_left/) | Determina si se usa la escritura de derecha a izquierda en un párrafo. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/es/aspose.slides/paragraphformat/latin_line_break/) | Determina si se usa el salto de línea latino en un párrafo. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/es/aspose.slides/paragraphformat/hanging_punctuation/) | Determina si se usa la puntuación colgante en un párrafo. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/es/aspose.slides/paragraphformat/margin_left/) | Devuelve o establece el margen izquierdo en un párrafo sin herencia.<br/>            Lectura/escritura **float**. |
| [`margin_right`](/slides/python-net/es/aspose.slides/paragraphformat/margin_right/) | Devuelve o establece el margen derecho en un párrafo sin herencia.<br/>            Lectura/escritura **float**. |
| [`indent`](/slides/python-net/es/aspose.slides/paragraphformat/indent/) | Devuelve o establece la sangría de primera línea/sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos.<br/>            Lectura/escritura **float**. |
| [`default_tab_size`](/slides/python-net/es/aspose.slides/paragraphformat/default_tab_size/) | Devuelve o establece el tamaño de tabulación predeterminado sin herencia.<br/>            Lectura/escritura **float**. |
| [`tabs`](/slides/python-net/es/aspose.slides/paragraphformat/tabs/) | Devuelve las tabulaciones de un párrafo. No se aplica herencia.<br/>            Solo lectura [`ITabCollection`](/slides/python-net/es/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/es/aspose.slides/paragraphformat/font_alignment/) | Devuelve o establece una alineación de fuente en un párrafo sin herencia.<br/>            Lectura/escritura [`FontAlignment`](/slides/python-net/es/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/es/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/es/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/es/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/es/aspose.slides/paragraphformat/default_portion_format/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/es/aspose.slides/paragraphformat/get_effective/#) | Obtiene los datos efectivos de formato de párrafo con la herencia aplicada. |


### Comentarios

Esta clase se usa para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo concreto. Esto significa que
            no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".


Para obtener los valores efectivos de los parámetros de formato, incluidos los heredados, debe usar el método [`ParagraphFormat.get_effective`](/slides/python-net/es/aspose.slides/paragraphformat/get_effective) 
            que devuelve una instancia de [`IParagraphFormatEffectiveData`](/slides/python-net/es/aspose.slides/iparagraphformateffectivedata).


### Ver también
* clase [`IParagraphFormatEffectiveData`](/slides/python-net/es/aspose.slides/iparagraphformateffectivedata)
* clase [`ParagraphFormat`](/slides/python-net/es/aspose.slides/paragraphformat)
* clase [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)