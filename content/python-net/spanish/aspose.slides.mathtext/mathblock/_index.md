---
title: MathBlock class
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathblock/
---
## MathBlock clase

Especifica una instancia de texto matemático que está contenida dentro de un MathParagraph y comienza en su propia línea.
            Todas las zonas matemáticas, incluidas ecuaciones, expresiones, matrices de ecuaciones o expresiones y fórmulas, están representadas por un bloque matemático.

**Herencia:**[`MathBlock`](/slides/python-net/es/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)

El tipo MathBlock expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/__init__/#) | Initializes a new instance of the MathBlock class. |
| [`__init__(self, math_element)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Creates a new mathematical block and puts specified element in it |
| [`__init__(self, math_elements)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`count`](/slides/python-net/es/aspose.slides.mathtext/mathblock/count/) | Obtiene el número de elementos matemáticos secundarios realmente contenidos en la colección.<br/>            Solo lectura **int**. |
| [`is_read_only`](/slides/python-net/es/aspose.slides.mathtext/mathblock/is_read_only/) | Devuelve false porque la colección de elementos secundarios puede ser modificada. |

Obtiene o establece IMathElement en el índice especificado.

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.mathtext/mathblock/__getitem__/) | El índice basado en cero del elemento |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/join/#imathelement) | Une un elemento matemático con este bloque matemático |
| [`join(self, math_text)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/join/#str) | Une un texto matemático con este bloque matemático |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/divide/#imathelement) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/divide/#str) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/enclose/#char-char) | Enmarca los elementos hijos de este bloque con caracteres especificados, como paréntesis u otros caracteres como marco |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Enmarca los elementos hijos de este bloque con caracteres especificados, como paréntesis u otros como marco<br/>            y delimita con un carácter separador |
| [`enclose(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/enclose/#) | Enmarca un elemento matemático entre paréntesis |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/function/#imathelement) | Toma una función de un argumento usando esta instancia como el nombre de la función |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/function/#str) | Toma una función de un argumento usando esta instancia como el nombre de la función |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Toma una función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Toma una función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Toma una función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Toma una función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Toma una función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Crea subíndice |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_subscript/#str) | Crea subíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Crea superíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_superscript/#str) | Crea superíndice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea subíndice y superíndice a la izquierda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Crea subíndice y superíndice a la izquierda |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/radical/#imathelement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/radical/#str) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Toma límite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Toma límite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Toma límite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Toma límite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operador N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Crea un operador N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Toma la integral |
| [`integral(self, integral_type)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Toma la integral sin límites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Toma la integral |
| [`group(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/group/#) | Coloca este elemento en un grupo usando una llave curva inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento en un grupo usando un carácter de agrupación, como una llave curva inferior u otro |
| [`to_border_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/to_border_box/#) | Coloca este elemento en un recuadro |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento en un recuadro |
| [`to_math_array(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/to_math_array/#) | Ubica los elementos hijos en una matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/accent/#char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [`overbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/overbar/#) | Establece una barra en la parte superior de este elemento |
| [`underbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/underbar/#) | Establece una barra en la parte inferior de este elemento |
| [`to_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/to_box/#) | Coloca este elemento en un recuadro no visual (agrupación lógica) <br/>            que se usa para agrupar componentes de una ecuación u otra instancia de texto matemático.<br/>            Un objeto en recuadro puede (por ejemplo) servir como emulador de operador con o sin punto de alineación, <br/>            servir como punto de salto de línea, o agruparse de manera que no permita saltos de línea dentro. |
| [`get_children(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/get_children/#) | Obtiene los elementos hijos |
| [`add(self, item)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/add/#imathelement) | Añade un elemento matemático al final de la colección. |
| [`clear(self)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/clear/#) | Elimina todos los elementos de la colección. |
| [`contains(self, item)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/contains/#imathelement) | Determina si la colección contiene un valor específico. |
| [`copy_to(self, array, array_index)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Copia a la matriz especificada. |
| [`remove(self, item)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/remove/#imathelement) | Elimina la primera aparición de un objeto específico de la colección. |
| [`index_of(self, item)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Determina el índice de un elemento matemático específico en la colección. |
| [`insert(self, index, item)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Inserta un MathElement en la colección en el índice especificado. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/remove_at/#int) | Elimina el elemento en el índice especificado de la colección. |
| [`join_block(self, other)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Une otro bloque matemático con este. |
| [`delimit(self, separator_character)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/delimit/#char) | Delimita los elementos hijos con un carácter separador (sin los corchetes) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/es/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Guarda el contenido de este [`MathBlock`](/slides/python-net/es/aspose.slides.mathtext/mathblock) como MathML |


### Ver también
* clase [`MathBlock`](/slides/python-net/es/aspose.slides.mathtext/mathblock)
* clase [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)