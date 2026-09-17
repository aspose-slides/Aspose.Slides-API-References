---
title: ChartPortionFormat class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat clase

Esta clase contiene las propiedades de formato de porciones de gráfico utilizadas en los gráficos.
            A diferencia de [`IPortionFormatEffectiveData`](/slides/python-net/es/aspose.slides/iportionformateffectivedata), todas las propiedades de esta clase son modificables.

**Inheritance:**[`ChartPortionFormat`](/slides/python-net/es/aspose.slides.charts/chartportionformat) → [`BasePortionFormat`](/slides/python-net/es/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)

El tipo ChartPortionFormat expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`line_format`](/slides/python-net/es/aspose.slides.charts/chartportionformat/line_format/) | Devuelve las propiedades LineFormat para el contorno del texto. No se aplica herencia.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides.charts/chartportionformat/fill_format/) | Devuelve las propiedades FillFormat del texto. No se aplica herencia.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides.charts/chartportionformat/effect_format/) | Devuelve las propiedades EffectFormat del texto. No se aplica herencia.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/es/aspose.slides.charts/chartportionformat/highlight_color/) | Devuelve el color usado para resaltar un texto. No se aplica herencia.<br/>            Solo lectura [`IColorFormat`](/slides/python-net/es/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/es/aspose.slides.charts/chartportionformat/underline_line_format/) | Devuelve las propiedades LineFormat usadas para delinear la línea subrayada. No se aplica herencia.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/es/aspose.slides.charts/chartportionformat/underline_fill_format/) | Devuelve las propiedades FillFormat de la línea subrayada. No se aplica herencia.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/es/aspose.slides.charts/chartportionformat/font_bold/) | Determina si la fuente está en negrita. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/es/aspose.slides.charts/chartportionformat/font_italic/) | Determina si la fuente es cursiva. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/es/aspose.slides.charts/chartportionformat/kumimoji/) | Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/es/aspose.slides.charts/chartportionformat/normalise_height/) | Determina si la altura del texto debe normalizarse. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/es/aspose.slides.charts/chartportionformat/proof_disabled/) | Determina si el texto no debe revisarse. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/es/aspose.slides.charts/chartportionformat/font_underline/) | Devuelve o establece el tipo de subrayado del texto. No se aplica herencia.<br/>            Lectura/escritura [`TextUnderlineType`](/slides/python-net/es/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/es/aspose.slides.charts/chartportionformat/text_cap_type/) | Devuelve o establece el tipo de capitalización del texto. No se aplica herencia.<br/>            Lectura/escritura [`TextCapType`](/slides/python-net/es/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/es/aspose.slides.charts/chartportionformat/strikethrough_type/) | Devuelve o establece el tipo de tachado del texto. No se aplica herencia.<br/>            Lectura/escritura [`TextStrikethroughType`](/slides/python-net/es/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/es/aspose.slides.charts/chartportionformat/is_hard_underline_line/) | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda<br/>            de las propiedades LineFormat del texto.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/es/aspose.slides.charts/chartportionformat/is_hard_underline_fill/) | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda<br/>            de las propiedades FillFormat del texto.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/es/aspose.slides.charts/chartportionformat/font_height/) | Devuelve o establece la altura de la fuente de una porción.<br/>            **float.NaN**  significa que la altura está indefinida y debe heredarse del Master.<br/>            Lectura/escritura **float**. |
| [`latin_font`](/slides/python-net/es/aspose.slides.charts/chartportionformat/latin_font/) | Devuelve o establece la información de fuente Latina.<br/>            Null significa que la fuente está indefinida y debe heredarse del Master.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/es/aspose.slides.charts/chartportionformat/east_asian_font/) | Devuelve o establece la información de fuente de Asia Oriental.<br/>            Null significa que la fuente está indefinida y debe heredarse del Master.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/es/aspose.slides.charts/chartportionformat/complex_script_font/) | Devuelve o establece la información de fuente de script complejo.<br/>            Null significa que la fuente está indefinida y debe heredarse del Master.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/es/aspose.slides.charts/chartportionformat/symbol_font/) | Devuelve o establece la información de fuente simbólica.<br/>            Null significa que la fuente está indefinida y debe heredarse del Master.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/es/aspose.slides.charts/chartportionformat/escapement/) | Devuelve o establece el texto en superíndice o subíndice.<br/>            Valor de -100% (subíndice) a 100% (superíndice).<br/>            **float.NaN**  significa que el valor está indefinido y debe heredarse del Master.<br/>            Lectura/escritura **float**. |
| [`kerning_minimal_size`](/slides/python-net/es/aspose.slides.charts/chartportionformat/kerning_minimal_size/) | Devuelve o establece el tamaño de fuente mínimo, para el cual debe activarse el interletraje.<br/>            **float.NaN**  significa que el valor está indefinido y debe heredarse del Master.<br/>            Lectura/escritura **float**. |
| [`language_id`](/slides/python-net/es/aspose.slides.charts/chartportionformat/language_id/) | Devuelve o establece el Id de un idioma de corrección. Usado para comprobar ortografía y gramática.<br/>            Lectura/escritura **str**. |
| [`alternative_language_id`](/slides/python-net/es/aspose.slides.charts/chartportionformat/alternative_language_id/) | Devuelve o establece el Id de un idioma alternativo.<br/>            Lectura/escritura **str**. |
| [`spacing`](/slides/python-net/es/aspose.slides.charts/chartportionformat/spacing/) | Devuelve o establece el incremento de espaciado entre caracteres.<br/>            **float.NaN**  significa que el valor está indefinido y debe heredarse del Master.<br/>            Lectura/escritura **float**. |
| [`spell_check`](/slides/python-net/es/aspose.slides.charts/chartportionformat/spell_check/) | Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto.<br/>            Cuando esta propiedad se establece en false, se suprimen las comprobaciones ortográficas para los elementos de texto.<br/>            Cuando se establece en true, la corrección ortográfica está permitida.<br/>            El valor predeterminado es `false`. |
| [`slide`](/slides/python-net/es/aspose.slides.charts/chartportionformat/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides.charts/chartportionformat/presentation/) |  |

### Observaciones

Esta clase se usa para devolver y manipular el formato de la porción de texto
            definido para la porción en particular. Esto significa que
            no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos
            obtendrá valores que significan "indefinido".

Para obtener los valores efectivos de los parámetros de formato, incluidos
            los heredados, debe utilizar el método [`PortionFormat.get_effective`](/slides/python-net/es/aspose.slides/portionformat/get_effective)
            que devuelve una instancia [`IPortionFormatEffectiveData`](/slides/python-net/es/aspose.slides/iportionformateffectivedata).

### Ver también
* clase [`BasePortionFormat`](/slides/python-net/es/aspose.slides/baseportionformat)
* clase [`ChartPortionFormat`](/slides/python-net/es/aspose.slides.charts/chartportionformat)
* clase [`IPortionFormatEffectiveData`](/slides/python-net/es/aspose.slides/iportionformateffectivedata)
* clase [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)