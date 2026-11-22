---
title: MathDelimiter class
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter clase

Especifica el objeto delimitador, compuesto por caracteres de apertura y cierre (como paréntesis, llaves, corchetes y barras verticales), y uno o más elementos matemáticos dentro, separados por un carácter especificado. Ejemplos: (𝑥2); [𝑥2|𝑦2]

**Herencia:**[`MathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)

El tipo MathDelimiter expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Inicializa MathDelimiter con el elemento especificado como argumento base único |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`arguments`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/arguments/) | Uno o más elementos matemáticos separados por caracteres delimitadores |
| [`beginning_character`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/beginning_character/) | El carácter de inicio del delimitador especifica el carácter delimitador de comienzo, o apertura. <br/>            Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves.<br/>            El valor predeterminado: '('. |
| [`separator_character`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/separator_character/) | El carácter separador del delimitador especifica el carácter que separa los argumentos en el objeto delimitador. <br/>            El valor predeterminado: '\|'. |
| [`ending_character`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/ending_character/) | El carácter de fin del delimitador especifica el carácter delimitador de cierre, o final. <br/>            Los delimitadores matemáticos son caracteres de cierre como paréntesis, corchetes y llaves.<br/>            El valor predeterminado: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Especifica el crecimiento de BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Cuando es true, los delimitadores crecen verticalmente para coincidir con la altura del operando.<br/>            El valor predeterminado es true |
| [`delimiter_shape`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Especifica la forma de los delimitadores en el objeto delimitador. <br/>            Cuando es MathDelimiterShape.Centered, los delimitadores se centran alrededor del eje matemático del texto matemático <br/>            y aún pueden ajustarse para cubrir toda la altura de su contenido.<br/>            Cuando es MathDelimiterShape.Match, su altura y forma se modifican para coincidir exactamente con su contenido. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Une un elemento matemático y forma un bloque matemático |
| [`join(self, math_text)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/join/#str) | Une un texto matemático y forma un bloque matemático |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/divide/#str) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`enclose(self)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/enclose/#) | Encierra un elemento matemático entre paréntesis |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Encierra un elemento matemático en caracteres especificados como paréntesis u otros caracteres como marco |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Toma una función de un argumento usando esta instancia como nombre de función |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/function/#str) | Toma una función de un argumento usando esta instancia como nombre de función |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Crea subíndice |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Crea subíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Crea superíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Crea superíndice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea subíndice y superíndice a la izquierda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Crea subíndice y superíndice a la izquierda |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/radical/#str) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Toma límite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Toma límite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Toma límite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Toma límite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operador N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Crea un operador N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Toma la integral |
| [`integral(self, integral_type)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Toma la integral sin límites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Toma la integral |
| [`group(self)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/group/#) | Coloca este elemento en un grupo usando una llave rizada inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento en un grupo usando un carácter de agrupación como una llave rizada inferior u otro |
| [`to_border_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Coloca este elemento en un recuadro con borde |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento en un recuadro con borde |
| [`to_math_array(self)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Inserta en una matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/accent/#char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [`overbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/overbar/#) | Establece una barra en la parte superior de este elemento |
| [`underbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/underbar/#) | Establece una barra en la parte inferior de este elemento |
| [`to_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/to_box/#) | Coloca este elemento en un cuadro no visual (agrupación lógica) <br/>            que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático.<br/>            Un objeto enmarcado puede (por ejemplo) servir como emulador de operador con o sin punto de alineación, <br/>            servir como punto de salto de línea, o agruparse de manera que no permita saltos de línea internos. |
| [`delimit(self, separator_character)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Delimita los argumentos usando el carácter delimitador especificado |
| [`get_children(self)`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter/get_children/#) | Obtiene los elementos hijos |

### Ver también
* clase [`MathDelimiter`](/slides/python-net/es/aspose.slides.mathtext/mathdelimiter)
* clase [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)