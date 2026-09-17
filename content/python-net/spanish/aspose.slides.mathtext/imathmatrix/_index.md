---
title: IMathMatrix class
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix clase

Especifica el objeto Matrix, constituido por elementos secundarios dispuestos en una o más filas y columnas. 
            Es importante notar que las matrices no tienen delimitadores incorporados. 
            Para colocar la matriz entre corchetes debe usar el objeto delimitador (IMathDelimiter).
            Los argumentos nulos pueden usarse para crear espacios vacíos en las matrices.

El tipo IMathMatrix expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`row_count`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/row_count/) | Número de filas en la matriz |
| [`column_count`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/column_count/) | Número de columnas en la matriz |
| [`hide_placeholders`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Ocultar los marcadores de posición para elementos de matriz vacíos<br/>            Predeterminado: false |
| [`base_justification`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/base_justification/) | Especifica la justificación vertical respecto al texto circundante. <br/>            Los valores posibles son top, bottom, y center.<br/>            Predeterminado: Center |
| [`min_column_width`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/min_column_width/) | Anchura mínima de columna en twips (1/20 de punto)<br/>            El espaciado de la brecha (también referido como “Column Gap” o “Gap Width”) se añade a <br/>            MinColumnWidth para determinar el espaciamiento total de columnas de la matriz<br/>            (distancia entre los mismos bordes de diferentes columnas).<br/>            Predeterminado: 0. |
| [`column_gap_rule`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | El tipo de espaciado horizontal entre columnas de una matriz; <br/>            Las unidades de espaciado horizontal pueden ser ems o points (almacenados como twips).<br/>            Predeterminado: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/column_gap/) | El valor del espaciado horizontal entre columnas de una matriz;<br/>            Si ColumnGapRule está configurado a 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de punto)<br/>            Si ColumnGapRule está configurado a 4 ("Multiple"), entonces la unidad se interpreta como número de incrementos de 0.5 em.<br/>            En otros casos se ignora.<br/>            Predeterminado: 0 |
| [`row_gap_rule`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | El tipo de espaciado vertical entre filas de una matriz; <br/>            Las unidades de espaciado vertical pueden ser lines o points (almacenados como twips).<br/>            Predeterminado: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/row_gap/) | El valor del espaciado vertical entre filas de una matriz;<br/>            Si RowGapRule está configurado a 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de punto)<br/>            Si RowGapRule está configurado a 4 ("Multiple"), entonces la unidad se interpreta como half-lines.<br/>            Predeterminado: 0 |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Obtiene la alineación horizontal de la columna especificada |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Establece la alineación horizontal de la columna especificada |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Establece la alineación horizontal de las columnas especificadas |
| [`insert_row_before(self, row_index)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Inserta una nueva fila antes de la especificada<br/>            Inicialmente todos los elementos de la nueva fila son None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Inserta una nueva fila después de la especificada<br/>            Inicialmente todos los elementos de la nueva fila son None. |
| [`delete_row(self, row_index)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Elimina la fila especificada |
| [`insert_column_before(self, column_index)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Inserta una nueva columna antes de la especificada<br/>            Inicialmente todos los elementos de la nueva columna son None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Inserta una nueva columna después de la especificada<br/>            Inicialmente todos los elementos de la nueva columna son None. |
| [`delete_column(self, column_index)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Elimina la columna especificada |
| [`get_children(self)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/es/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Ver también
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)