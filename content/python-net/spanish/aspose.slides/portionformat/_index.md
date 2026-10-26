---
title: PortionFormat class
second_title: Referencia API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/portionformat/
---
## Clase PortionFormat

Esta clase contiene las propiedades de formato de porción de texto. A diferencia de [`IPortionFormatEffectiveData`](/slides/python-net/es/aspose.slides/iportionformateffectivedata), todas las propiedades de esta clase son modificables.

**Herencia:**[`PortionFormat`](/slides/python-net/es/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/es/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)

El tipo PortionFormat expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides/portionformat/__init__/#) | Inicializa una nueva instancia de la clase [`PortionFormat`](/slides/python-net/es/aspose.slides/portionformat). |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`line_format`](/slides/python-net/es/aspose.slides/portionformat/line_format/) | Devuelve las propiedades LineFormat para el contorno del texto. No se aplica herencia.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/portionformat/fill_format/) | Devuelve las propiedades FillFormat del texto. No se aplica herencia.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/portionformat/effect_format/) | Devuelve las propiedades EffectFormat del texto. No se aplica herencia.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/es/aspose.slides/portionformat/highlight_color/) | Devuelve el color usado para resaltar un texto. No se aplica herencia.<br/>            Solo lectura [`IColorFormat`](/slides/python-net/es/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/es/aspose.slides/portionformat/underline_line_format/) | Devuelve las propiedades LineFormat usadas para delinear la línea de subrayado. No se aplica herencia.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/es/aspose.slides/portionformat/underline_fill_format/) | Devuelve las propiedades FillFormat de la línea de subrayado. No se aplica herencia.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/es/aspose.slides/portionformat/font_bold/) | Determina si la fuente es negrita. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/es/aspose.slides/portionformat/font_italic/) | Determina si la fuente es itálica. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/es/aspose.slides/portionformat/kumimoji/) | Determina si los números deben ignorar la disposición vertical del texto específica de lenguas orientales. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/es/aspose.slides/portionformat/normalise_height/) | Determina si la altura del texto debe normalizarse. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/es/aspose.slides/portionformat/proof_disabled/) | Determina si el texto no debe revisarse ortográficamente. No se aplica herencia.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/es/aspose.slides/portionformat/font_underline/) | Devuelve o establece el tipo de subrayado del texto. No se aplica herencia.<br/>            Lectura/escritura [`TextUnderlineType`](/slides/python-net/es/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/es/aspose.slides/portionformat/text_cap_type/) | Devuelve o establece el tipo de capitalización del texto. No se aplica herencia.<br/>            Lectura/escritura [`TextCapType`](/slides/python-net/es/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/es/aspose.slides/portionformat/strikethrough_type/) | Devuelve o establece el tipo de tachado del texto. No se aplica herencia.<br/>            Lectura/escritura [`TextStrikethroughType`](/slides/python-net/es/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/es/aspose.slides/portionformat/is_hard_underline_line/) | Determina si el estilo de subrayado tiene sus propias propiedades LineFormat o las hereda<br/>            de las propiedades LineFormat del texto.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/es/aspose.slides/portionformat/is_hard_underline_fill/) | Determina si el estilo de subrayado tiene sus propias propiedades FillFormat o las hereda<br/>            de las propiedades FillFormat del texto.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/es/aspose.slides/portionformat/font_height/) | Devuelve o establece la altura de fuente de una porción.<br/>            **float.NaN**  indica que la altura no está definida y debe heredarse del Master.<br/>            Lectura/escritura **float**. |
| [`latin_font`](/slides/python-net/es/aspose.slides/portionformat/latin_font/) | Devuelve o establece la información de fuente latina.<br/>            Null indica que la fuente no está definida y debe heredarse del Master.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/es/aspose.slides/portionformat/east_asian_font/) | Devuelve o establece la información de fuente del Este Asiático.<br/>            Null indica que la fuente no está definida y debe heredarse del Master.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/es/aspose.slides/portionformat/complex_script_font/) | Devuelve o establece la información de fuente de scripts complejos.<br/>            Null indica que la fuente no está definida y debe heredarse del Master.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/es/aspose.slides/portionformat/symbol_font/) | Devuelve o establece la información de fuente simbólica.<br/>            Null indica que la fuente no está definida y debe heredarse del Master.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/es/aspose.slides/portionformat/escapement/) | Devuelve o establece el texto en superíndice o subíndice.<br/>            Valor de -100% (subíndice) a 100% (superíndice).<br/>            **float.NaN**  indica que el valor no está definido y debe heredarse del Master.<br/>            Lectura/escritura **float**. |
| [`kerning_minimal_size`](/slides/python-net/es/aspose.slides/portionformat/kerning_minimal_size/) | Devuelve o establece el tamaño mínimo de fuente, para el cual el kerning debe activarse.<br/>            **float.NaN**  indica que el valor no está definido y debe heredarse del Master.<br/>            Lectura/escritura **float**. |
| [`language_id`](/slides/python-net/es/aspose.slides/portionformat/language_id/) | Devuelve o establece el Id de un idioma de revisión. Usado para comprobar ortografía y gramática.<br/>            Lectura/escritura **str**. |
| [`alternative_language_id`](/slides/python-net/es/aspose.slides/portionformat/alternative_language_id/) | Devuelve o establece el Id de un idioma alternativo.<br/>            Lectura/escritura **str**. |
| [`spacing`](/slides/python-net/es/aspose.slides/portionformat/spacing/) | Devuelve o establece el incremento de espaciado entre caracteres.<br/>            **float.NaN**  indica que el valor no está definido y debe heredarse del Master.<br/>            Lectura/escritura **float**. |
| [`spell_check`](/slides/python-net/es/aspose.slides/portionformat/spell_check/) | Obtiene o establece un valor que indica si la corrección ortográfica está habilitada para la porción de texto.<br/>            Cuando esta propiedad se establece en false, se suprimen las verificaciones ortográficas para los elementos de texto.<br/>            Cuando se establece en true, se permite la corrección ortográfica.<br/>            El valor predeterminado es `false`. |
| [`bookmark_id`](/slides/python-net/es/aspose.slides/portionformat/bookmark_id/) | Devuelve o establece el identificador del marcador.<br/>            Lectura/escritura **str**. |
| [`smart_tag_clean`](/slides/python-net/es/aspose.slides/portionformat/smart_tag_clean/) | Determina si la etiqueta inteligente debe limpiarse. No se aplica herencia.<br/>            Lectura/escritura **bool**. |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/portionformat/hyperlink_click/) | Devuelve o establece el hipervínculo definido para clic del ratón.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/portionformat/hyperlink_mouse_over/) | Devuelve o establece el hipervínculo definido para pasar el ratón por encima.<br/>            Lectura/escritura [`IHyperlink`](/slides/python-net/es/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/portionformat/hyperlink_manager/) | Gestor de hipervínculos.<br/>            Solo lectura [`IHyperlinkManager`](/slides/python-net/es/aspose.slides/ihyperlinkmanager). |
| [`slide`](/slides/python-net/es/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/portionformat/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/es/aspose.slides/portionformat/get_effective/#) | Obtiene los datos de formato de porción efectivos con la herencia aplicada. |


### Observaciones

Esta clase se usa para devolver y manipular las propiedades de formato de porciones de texto definidas para la porción particular. Esto significa que
            no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores de los parámetros de formato efectivos, incluidas las herencias, debe usar el método [`PortionFormat.get_effective`](/slides/python-net/es/aspose.slides/portionformat/get_effective) 
            que devuelve una instancia [`IPortionFormatEffectiveData`](/slides/python-net/es/aspose.slides/iportionformateffectivedata).

### Ver también
* clase [`BasePortionFormat`](/slides/python-net/es/aspose.slides/baseportionformat)
* clase [`IPortionFormatEffectiveData`](/slides/python-net/es/aspose.slides/iportionformateffectivedata)
* clase [`PortionFormat`](/slides/python-net/es/aspose.slides/portionformat)
* clase [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)