---
title: MathNaryOperator class
second_title: Aspose.Slides para Python vía .NET API Reference
description: 
type: docs
url: /es/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator clase

Especifica un objeto matemático N-ario, como Summation e Integral. Consiste en un operador, una base (u operando), y límites superior e inferior opcionales. Ejemplos de operadores N-arios son: Summation, Union, Intersection, Integral

**Herencia:**[`MathNaryOperator`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)

El tipo MathNaryOperator expone los siguientes miembros:

## Constructors

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Initializes a new instance of the MathNaryOperator class. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Initializes a new instance of the MathNaryOperator class. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Initializes a new instance of the MathNaryOperator class. |

## Properties

| Propiedad | Descripción |
| :- | :- |
| [`base`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/base/) | Argumento base |
| [`subscript`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/subscript/) | Especifica un argumento de subíndice que, por ejemplo, en el caso de un integral, establece el límite inferior |
| [`superscript`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/superscript/) | Especifica un argumento de superíndice que, por ejemplo, en el caso de un integral, establece el límite superior |
| [`operator`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/operator/) | Carácter del Operador Nario<br/>            Por ejemplo: '∑', '∫' |
| [`limit_location`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/limit_location/) | La ubicación de los límites (subíndice y superíndice) |
| [`grow_to_match_operand_height`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | El carácter del operador crece verticalmente para coincidir con la altura de su operando |
| [`hide_subscript`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Ocultar subíndice |
| [`hide_superscript`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Ocultar superíndice |

## Methods

| Método | Descripción |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Une un elemento matemático y forma un bloque matemático |
| [`join(self, math_text)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/join/#str) | Une un texto matemático y forma un bloque matemático |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`enclose(self)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Encierra un elemento matemático entre paréntesis |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/function/#str) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Crea subíndice |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Crea subíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Crea superíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Crea superíndice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea subíndice y superíndice a la izquierda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Crea subíndice y superíndice a la izquierda |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Toma el límite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Toma el límite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Toma el límite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Toma el límite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operador N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Crea un operador N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Toma la integral |
| [`integral(self, integral_type)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Toma la integral sin límites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Toma la integral |
| [`group(self)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/group/#) | Coloca este elemento en un grupo usando una llave rizada inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento en un grupo usando un carácter de agrupación como una llave rizada inferior u otro |
| [`to_border_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Coloca este elemento en un cuadro de borde |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento en un cuadro de borde |
| [`to_math_array(self)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Coloca en una matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [`overbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Establece una barra en la parte superior de este elemento |
| [`underbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Establece una barra en la parte inferior de este elemento |
| [`to_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Coloca este elemento en una caja no visual (agrupación lógica) <br/>            que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático.<br/>            Un objeto en caja puede (por ejemplo) servir como emulador de operador con o sin punto de alineación, <br/>            servir como punto de salto de línea, o estar agrupado de manera que no permita saltos de línea dentro. |
| [`get_children(self)`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Obtiene elementos hijos |

### Ver también
* clase [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)
* clase [`MathNaryOperator`](/slides/python-net/es/aspose.slides.mathtext/mathnaryoperator)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)