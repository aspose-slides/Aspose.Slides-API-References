---
title: IParagraphFormat class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/iparagraphformat/
---
## IParagraphFormat clase

Esta clase contiene las propiedades de formato de párrafo. A diferencia de [`IParagraphFormatEffectiveData`](/slides/python-net/es/aspose.slides/iparagraphformateffectivedata), todas las propiedades de esta clase son modificables.

El tipo IParagraphFormat expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`bullet`](/slides/python-net/es/aspose.slides/iparagraphformat/bullet/) | Devuelve el formato de viñeta del párrafo.<br/>            Solo lectura [`IBulletFormat`](/slides/python-net/es/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/es/aspose.slides/iparagraphformat/depth/) | Devuelve o establece la profundidad del párrafo.<br/>            El valor 0 significa valor indefinido.<br/>            Lectura/escritura **int**. |
| [`alignment`](/slides/python-net/es/aspose.slides/iparagraphformat/alignment/) | Devuelve o establece la alineación del texto en un párrafo sin herencia.<br/>            Lectura/escritura [`TextAlignment`](/slides/python-net/es/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/es/aspose.slides/iparagraphformat/space_within/) | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo significa porcentaje, negativo - tamaño en puntos. No se aplica herencia.<br/>            Lectura/escritura **float**. |
| [`space_before`](/slides/python-net/es/aspose.slides/iparagraphformat/space_before/) | Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia.<br/>            Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco.<br/>            Un valor negativo especifica el tamaño del espacio en blanco en puntos.<br/>            Lectura/escritura **float**. |
| [`space_after`](/slides/python-net/es/aspose.slides/iparagraphformat/space_after/) | Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia.<br/>            Un valor positivo especifica el porcentaje del tamaño de fuente que debe tener el espacio en blanco.<br/>            Un valor negativo especifica el tamaño del espacio en blanco en puntos.<br/>            Lectura/escritura **float**. |
| [`east_asian_line_break`](/slides/python-net/es/aspose.slides/iparagraphformat/east_asian_line_break/) | Determina si se usa el salto de línea de Asia Oriental en un párrafo. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/es/aspose.slides/iparagraphformat/right_to_left/) | Determina si la escritura de derecha a izquierda se usa en un párrafo. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/es/aspose.slides/iparagraphformat/latin_line_break/) | Determina si se usa el salto de línea latino en un párrafo. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/es/aspose.slides/iparagraphformat/hanging_punctuation/) | Determina si se usa la puntuación colgante en un párrafo. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/es/aspose.slides/iparagraphformat/margin_left/) | Devuelve o establece el margen izquierdo en un párrafo sin herencia.<br/>            Lectura/escritura **float**. |
| [`margin_right`](/slides/python-net/es/aspose.slides/iparagraphformat/margin_right/) | Devuelve o establece el margen derecho en un párrafo sin herencia.<br/>            Lectura/escritura **float**. |
| [`indent`](/slides/python-net/es/aspose.slides/iparagraphformat/indent/) | Devuelve o establece la sangría de primera línea/sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos.<br/>            Lectura/escritura **float**. |
| [`default_tab_size`](/slides/python-net/es/aspose.slides/iparagraphformat/default_tab_size/) | Devuelve o establece el tamaño de tabulación predeterminado sin herencia.<br/>            Lectura/escritura **float**. |
| [`tabs`](/slides/python-net/es/aspose.slides/iparagraphformat/tabs/) | Devuelve las tabulaciones de un párrafo. No se aplica herencia.<br/>            Solo lectura [`ITabCollection`](/slides/python-net/es/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/es/aspose.slides/iparagraphformat/font_alignment/) | Devuelve o establece una alineación de fuente en un párrafo sin herencia.<br/>            Lectura/escritura [`FontAlignment`](/slides/python-net/es/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/es/aspose.slides/iparagraphformat/default_portion_format/) | Devuelve el formato de porción predeterminado de un párrafo. No se aplica herencia.<br/>            Solo lectura [`IPortionFormat`](/slides/python-net/es/aspose.slides/iportionformat). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/es/aspose.slides/iparagraphformat/get_effective/#) | Obtiene los datos de formato de párrafo efectivos con la herencia aplicada. |

### Observaciones

Esta clase se usa para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo en particular. Esto significa que
            no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "indefinido".

Para obtener los valores de los parámetros de formato efectivos, incluidos los heredados, necesita usar el método [`IParagraphFormat.get_effective`](/slides/python-net/es/aspose.slides/iparagraphformat/get_effective) 
            que devuelve una instancia de [`IParagraphFormatEffectiveData`](/slides/python-net/es/aspose.slides/iparagraphformateffectivedata).

### Ver también
* clase [`IParagraphFormatEffectiveData`](/slides/python-net/es/aspose.slides/iparagraphformateffectivedata)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)