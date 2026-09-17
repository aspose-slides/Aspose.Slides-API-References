---
title: MathMatrix class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix clase

Especifica el objeto Matrix, compuesto por elementos secundarios dispuestos en una o más filas y columnas. 
            Es importante señalar que las matrices no tienen delimitadores incorporados. 
            Para colocar la matriz entre corchetes debe usar el objeto delimitador (IMathDelimiter). 
            Los argumentos nulos pueden usarse para crear espacios en blanco en las matrices.

**Herencia:**[`MathMatrix`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)

El tipo MathMatrix expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Inicializa una nueva instancia de la clase MathMatrix. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`row_count`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/row_count/) | Número de filas en la matriz |
| [`column_count`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/column_count/) | Número de columnas en la matriz |
| [`hide_placeholders`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Ocultar los marcadores de posición para elementos de matriz vacíos<br/>            Predeterminado: false |
| [`base_justification`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/base_justification/) | Especifica la justificación vertical respecto al texto circundante. <br/>            Los valores posibles son top, bottom y center.<br/>            Predeterminado: Center |
| [`min_column_width`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/min_column_width/) | Ancho mínimo de columna en twips (1/20 de punto)<br/>            El espaciado de la brecha (también llamado “Column Gap” o “Gap Width”) se suma al <br/>            MinColumnWidth para determinar el espaciado total de columnas de la matriz<br/>            (distancia entre los mismos bordes de diferentes columnas).<br/>            Predeterminado: 0. |
| [`column_gap_rule`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | El tipo de espaciado horizontal entre columnas de una matriz; <br/>            Las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips).<br/>            Predeterminado: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/column_gap/) | El valor del espaciado horizontal entre columnas de una matriz;<br/>            Si ColumnGapRule está configurado a 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de punto)<br/>            Si ColumnGapRule está configurado a 4 ("Multiple"), entonces la unidad se interpreta como número de incrementos de 0.5 em.<br/>            En otros casos se ignora.<br/>            Predeterminado: 0 |
| [`row_gap_rule`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | El tipo de espaciado vertical entre filas de una matriz; <br/>            Las unidades de espaciado vertical pueden ser líneas o puntos (almacenados como twips).<br/>            Predeterminado: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/row_gap/) | El valor del espaciado vertical entre filas de una matriz;<br/>            Si RowGapRule está configurado a 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de punto)<br/>            Si RowGapRule está configurado a 4 ("Multiple"), entonces la unidad se interpreta como medias líneas.<br/>            Predeterminado: 0 |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Une un elemento matemático y forma un bloque matemático |
| [`join(self, math_text)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/join/#str) | Une un texto matemático y forma un bloque matemático |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/divide/#str) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`enclose(self)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/enclose/#) | Encierra un elemento matemático entre paréntesis |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Encierra un elemento matemático en caracteres especificados como paréntesis u otros caracteres como encuadre |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/function/#str) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Crea subíndice |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Crea subíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Crea superíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Crea superíndice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea subíndice y superíndice a la izquierda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Crea subíndice y superíndice a la izquierda |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/radical/#str) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Toma límite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Toma límite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Toma límite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Toma límite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operador N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Crea un operador N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Toma la integral |
| [`integral(self, integral_type)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Toma la integral sin límites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Toma la integral |
| [`group(self)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/group/#) | Coloca este elemento en un grupo usando una llave rizada inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento en un grupo usando un carácter de agrupación como una llave rizada inferior u otro |
| [`to_border_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Coloca este elemento en un recuadro con borde |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento en un recuadro con borde |
| [`to_math_array(self)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Coloca en una matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/accent/#char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [`overbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/overbar/#) | Establece una barra en la parte superior de este elemento |
| [`underbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/underbar/#) | Establece una barra en la parte inferior de este elemento |
| [`to_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/to_box/#) | Coloca este elemento en un cuadro no visual (agrupación lógica) <br/>            que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático.<br/>            Un objeto en cuadro puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, <br/>            servir como punto de salto de línea, o agruparse de manera que no permita saltos de línea dentro. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Obtiene la alineación horizontal de la columna especificada |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Establece la alineación horizontal de la columna especificada |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Establece la alineación horizontal de las columnas especificadas |
| [`insert_row_before(self, row_index)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Inserta una nueva fila antes de la especificada<br/>            Inicialmente todos los elementos de la nueva fila son None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Inserta una nueva fila después de la especificada<br/>            Inicialmente todos los elementos de la nueva fila son None. |
| [`delete_row(self, row_index)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Elimina la fila especificada |
| [`insert_column_before(self, column_index)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Inserta una nueva columna antes de la especificada<br/>            Inicialmente todos los elementos de la nueva columna son None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Inserta una nueva columna después de la especificada<br/>            Inicialmente todos los elementos de la nueva columna son None. |
| [`delete_column(self, column_index)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Elimina la columna especificada |
| [`get_children(self)`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix/get_children/#) | Obtiene los elementos hijos |


### Ver también
* clase [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)
* clase [`MathMatrix`](/slides/python-net/es/aspose.slides.mathtext/mathmatrix)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)