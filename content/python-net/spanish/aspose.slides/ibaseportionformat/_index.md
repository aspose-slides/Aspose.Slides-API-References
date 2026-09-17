---
title: IBasePortionFormat class
second_title: Referencia de la API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat clase

Esta clase contiene las propiedades de formato de porción de texto. A diferencia de [`IPortionFormatEffectiveData`](/slides/python-net/es/aspose.slides/iportionformateffectivedata), todas las propiedades de esta clase son modificables.

El tipo IBasePortionFormat expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`line_format`](/slides/python-net/es/aspose.slides/ibaseportionformat/line_format/) | Devuelve las propiedades LineFormat para el contorno del texto. No se aplica herencia.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/ibaseportionformat/fill_format/) | Devuelve las propiedades FillFormat del texto. No se aplica herencia.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/ibaseportionformat/effect_format/) | Devuelve las propiedades EffectFormat del texto. No se aplica herencia.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/es/aspose.slides/ibaseportionformat/highlight_color/) | Devuelve el color usado para resaltar un texto. No se aplica herencia.<br/>            Solo lectura [`IColorFormat`](/slides/python-net/es/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/es/aspose.slides/ibaseportionformat/underline_line_format/) | Devuelve las propiedades LineFormat usadas para delinear la línea subrayada. No se aplica herencia.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/es/aspose.slides/ibaseportionformat/underline_fill_format/) | Devuelve las propiedades FillFormat de la línea subrayada. No se aplica herencia.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/es/aspose.slides/ibaseportionformat/font_bold/) | Determina si la fuente está en negrita. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/es/aspose.slides/ibaseportionformat/font_italic/) | Determina si la fuente está en cursiva. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/es/aspose.slides/ibaseportionformat/kumimoji/) | Determina si los números deben ignorar la disposición vertical del texto específica de idiomas orientales. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/es/aspose.slides/ibaseportionformat/normalise_height/) | Determina si la altura del texto debe ser normalizada. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/es/aspose.slides/ibaseportionformat/proof_disabled/) | Determina si el texto no debe ser revisado. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/es/aspose.slides/ibaseportionformat/font_underline/) | Devuelve o establece el tipo de subrayado del texto. No se aplica herencia.<br/>            Lectura/escritura [`TextUnderlineType`](/slides/python-net/es/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/es/aspose.slides/ibaseportionformat/text_cap_type/) | Devuelve o establece el tipo de capitalización del texto. No se aplica herencia.<br/>            Lectura/escritura [`TextCapType`](/slides/python-net/es/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/es/aspose.slides/ibaseportionformat/strikethrough_type/) | Devuelve o establece el tipo de tachado del texto. No se aplica herencia.<br/>            Lectura/escritura [`TextStrikethroughType`](/slides/python-net/es/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/es/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda<br/>            de las propiedades LineFormat del texto.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/es/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda<br/>            de las propiedades FillFormat del texto.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/es/aspose.slides/ibaseportionformat/font_height/) | Devuelve o establece la altura de fuente de una porción.<br/>            **float.NaN**  significa que la altura no está definida y debe heredarse del Maestro.<br/>            Lectura/escritura **float**. |
| [`latin_font`](/slides/python-net/es/aspose.slides/ibaseportionformat/latin_font/) | Devuelve o establece la información de fuente latina.<br/>            Null significa que la fuente no está definida y debe heredarse del Maestro.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/es/aspose.slides/ibaseportionformat/east_asian_font/) | Devuelve o establece la información de fuente de Asia Oriental.<br/>            Null significa que la fuente no está definida y debe heredarse del Maestro.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/es/aspose.slides/ibaseportionformat/complex_script_font/) | Devuelve o establece la información de fuente de script complejo.<br/>            Null significa que la fuente no está definida y debe heredarse del Maestro.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/es/aspose.slides/ibaseportionformat/symbol_font/) | Devuelve o establece la información de fuente simbólica.<br/>            Null significa que la fuente no está definida y debe heredarse del Maestro.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/es/aspose.slides/ibaseportionformat/escapement/) | Devuelve o establece el texto en superíndice o subíndice.<br/>            Valor de -100% (subíndice) a 100% (superíndice).<br/>            **float.NaN**  significa que el valor no está definido y debe heredarse del Maestro.<br/>            Lectura/escritura **float**. |
| [`kerning_minimal_size`](/slides/python-net/es/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Devuelve o establece el tamaño mínimo de fuente, para el cual el ajuste de pares debe activarse.<br/>            **float.NaN**  significa que el valor no está definido y debe heredarse del Maestro.<br/>            Lectura/escritura **float**. |
| [`language_id`](/slides/python-net/es/aspose.slides/ibaseportionformat/language_id/) | Devuelve o establece el Id de un idioma de revisión. Usado para comprobar la ortografía y la gramática.<br/>            Lectura/escritura **str**. |
| [`alternative_language_id`](/slides/python-net/es/aspose.slides/ibaseportionformat/alternative_language_id/) | Devuelve o establece el Id de un idioma alternativo.<br/>            Lectura/escritura **str**. |
| [`spacing`](/slides/python-net/es/aspose.slides/ibaseportionformat/spacing/) | Devuelve o establece el incremento de espaciado intercaracter.<br/>            **float.NaN**  significa que el valor no está definido y debe heredarse del Maestro.<br/>            Lectura/escritura **float**. |
| [`spell_check`](/slides/python-net/es/aspose.slides/ibaseportionformat/spell_check/) | Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto.<br/>            Cuando esta propiedad se establece en false, las verificaciones ortográficas para los elementos de texto se suprimen.<br/>            Cuando se establece en true, se permite la corrección ortográfica.<br/>            El valor predeterminado es `false`. |

### Observaciones

Esta clase se usa para devolver y manipular las propiedades de formato de porción de texto definidas para la porción en particular. Esto significa que
            no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores efectivos de los parámetros de formato, incluidos los heredados, debe utilizar el método [`IPortionFormat.get_effective`](/slides/python-net/es/aspose.slides/iportionformat/get_effective) 
            que devuelve una instancia [`IPortionFormatEffectiveData`](/slides/python-net/es/aspose.slides/iportionformateffectivedata).

### Ver también
* clase [`IPortionFormatEffectiveData`](/slides/python-net/es/aspose.slides/iportionformateffectivedata)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)