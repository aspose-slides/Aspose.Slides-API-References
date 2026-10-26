---
title: IBulletFormat class
second_title: Aspose.Slides para Python mediante la Referencia de API .NET
description: 
type: docs
url: /es/aspose.slides/ibulletformat/
---
## IBulletFormat clase

Representa las propiedades de formato de viñeta de párrafo.

El tipo IBulletFormat expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`type`](/slides/python-net/es/aspose.slides/ibulletformat/type/) | Devuelve o establece el tipo de viñeta de un párrafo sin herencia.<br/>            Lectura/escritura [`BulletType`](/slides/python-net/es/aspose.slides/bullettype). |
| [`char`](/slides/python-net/es/aspose.slides/ibulletformat/char/) | Devuelve o establece el carácter de viñeta de un párrafo sin herencia.<br/>            Lectura/escritura **System.Char**. |
| [`font`](/slides/python-net/es/aspose.slides/ibulletformat/font/) | Devuelve o establece la fuente de la viñeta de un párrafo sin herencia.<br/>            Lectura/escritura [`IFontData`](/slides/python-net/es/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/es/aspose.slides/ibulletformat/height/) | Devuelve o establece la altura de la viñeta de un párrafo sin herencia.<br/>            El valor float.NaN indica que la viñeta hereda la altura de la primera porción del párrafo.<br/>            Lectura/escritura **float**. |
| [`color`](/slides/python-net/es/aspose.slides/ibulletformat/color/) | Devuelve el formato de color de una viñeta de un párrafo sin herencia.<br/>            Solo lectura [`IColorFormat`](/slides/python-net/es/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/es/aspose.slides/ibulletformat/picture/) | Devuelve la imagen usada como viñeta en un párrafo sin herencia.<br/>            Solo lectura [`ISlidesPicture`](/slides/python-net/es/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/es/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Devuelve o establece el primer número que se usa para el grupo de viñetas numeradas sin herencia.<br/>            Lectura/escritura **int**. |
| [`numbered_bullet_style`](/slides/python-net/es/aspose.slides/ibulletformat/numbered_bullet_style/) | Devuelve o establece el estilo de una viñeta numerada sin herencia.<br/>            Lectura/escritura [`IBulletFormat.numbered_bullet_style`](/slides/python-net/es/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/es/aspose.slides/ibulletformat/is_bullet_hard_color/) | Determina si la viñeta tiene color propio o lo hereda de la primera porción del párrafo.<br/>            **NullableBool.True**  si la viñeta tiene color propio y **NullableBool.False**  si la viñeta<br/>            hereda el color de la primera porción del párrafo.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/es/aspose.slides/ibulletformat/is_bullet_hard_font/) | Determina si la viñeta tiene fuente propia o la hereda de la primera porción del párrafo.<br/>            **NullableBool.True**  si la viñeta tiene fuente propia y **NullableBool.False**  si la viñeta<br/>            hereda la fuente de la primera porción del párrafo.<br/>            Lectura/escritura [`NullableBool`](/slides/python-net/es/aspose.slides/nullablebool). |

## Métodos

| Método | Descripción |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/es/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Establece desplazamientos predeterminados distintos de cero para el Indent y MarginLeft efectivos del párrafo cuando las viñetas están habilitadas (como hace PowerPoint si se habilitan las viñetas/numeración del párrafo). Si las viñetas están deshabilitadas, simplemente restablece el Indent y MarginLeft del párrafo (como hace PowerPoint si se deshabilitan las viñetas/numeración del párrafo). Los desplazamientos de sangría se aplican en relación al contexto actual de la viñeta: IBulletFormat.Type, .NumberedBulletStyle y FontHeight de la primera porción. Los desplazamientos de sangría distintos de cero se aplican al Indent y MarginLeft efectivos del párrafo actual (haciendo que los valores resultantes sean locales). |
| [`get_effective(self)`](/slides/python-net/es/aspose.slides/ibulletformat/get_effective/#) | Obtiene los datos efectivos de formato de viñeta con la herencia aplicada. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)