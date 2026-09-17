---
title: BulletFormat class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/bulletformat/
---
## BulletFormat clase

Representa las propiedades de formato de viñeta de un párrafo.

**Inheritance:**[`BulletFormat`](/slides/python-net/es/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)

El tipo BulletFormat expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/es/aspose.slides/bulletformat/type/) | Devuelve o establece el tipo de viñeta de un párrafo sin herencia.<br/>            Lectura/escritura [`BulletType`](/slides/python-net/es/aspose.slides/bullettype). |
| [`char`](/slides/python-net/es/aspose.slides/bulletformat/char/) | Devuelve o establece el carácter de viñeta de un párrafo sin herencia.<br/>            Lectura/escritura **System.Char**. |
| [`font`](/slides/python-net/es/aspose.slides/bulletformat/font/) | Devuelve o establece la fuente de la viñeta de un párrafo sin herencia.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/es/aspose.slides/bulletformat/height/) | Devuelve o establece la altura de la viñeta de un párrafo sin herencia.<br/>            El valor float.NaN determina que la viñeta hereda la altura de la primera porción del párrafo.<br/>            Lectura/escritura **float**. |
| [`color`](/slides/python-net/es/aspose.slides/bulletformat/color/) | Devuelve el formato de color de una viñeta de un párrafo sin herencia.<br/>            Solo lectura [`IColorFormat`](/slides/python-net/es/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/es/aspose.slides/bulletformat/numbered_bullet_start_with/) | Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia.<br/>            Lectura/escritura **int**. |
| [`numbered_bullet_style`](/slides/python-net/es/aspose.slides/bulletformat/numbered_bullet_style/) | Devuelve o establece el estilo de una viñeta numerada sin herencia.<br/>            Lectura/escritura [`NumberedBulletStyle`](/slides/python-net/es/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/es/aspose.slides/bulletformat/is_bullet_hard_color/) | Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo.<br/>            **NullableBool.True**  si la viñeta tiene color propio y **NullableBool.False**  si la viñeta<br/>            hereda el color de la primera porción del párrafo.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/es/aspose.slides/bulletformat/is_bullet_hard_font/) | Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo.<br/>            **NullableBool.True**  si la viñeta tiene fuente propia y **NullableBool.False**  si la viñeta<br/>            hereda la fuente de la primera porción del párrafo.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/es/aspose.slides/bulletformat/picture/) | Devuelve la imagen usada como viñeta en un párrafo sin herencia.<br/>            Solo lectura [`ISlidesPicture`](/slides/python-net/es/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/es/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/bulletformat/presentation/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/es/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Establece los desplazamientos predeterminados distintos de cero para el Indent y el MarginLeft del párrafo efectivo cuando las viñetas están habilitadas (como PowerPoint hace al habilitar viñetas/numeración de párrafo). Si las viñetas están deshabilitadas, simplemente restablece el Indent y el MarginLeft del párrafo (como PowerPoint hace al deshabilitar viñetas/numeración de párrafo). Los desplazamientos de sangrado se aplican con respecto al contexto actual de la viñeta: IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangrado distintos de cero se aplican al Indent y al MarginLeft efectivos del párrafo actual (haciendo que los valores resultantes sean valores locales). |
| [`get_effective(self)`](/slides/python-net/es/aspose.slides/bulletformat/get_effective/#) | Obtiene los datos de formato de viñeta efectivos con la herencia aplicada. |


### Ver también
* clase [`BulletFormat`](/slides/python-net/es/aspose.slides/bulletformat)
* clase [`PVIObject`](/slides/python-net/es/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)