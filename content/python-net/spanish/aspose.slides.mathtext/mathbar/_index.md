---
title: MathBar class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathbar/
---
## MathBar clase

Especifica la función de barra, compuesta por un argumento base y una barra superior o inferior

**Herencia:**[`MathBar`](/slides/python-net/es/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)

El tipo MathBar expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/__init__/#imathelement) | Inicializa MathBar con barra superior (posición superior) |
| [`__init__(self, element, position)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | Inicializa MathBar con la posición especificada |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`base`](/slides/python-net/es/aspose.slides.mathtext/mathbar/base/) | Argumento base |
| [`position`](/slides/python-net/es/aspose.slides.mathtext/mathbar/position/) | Posición de la línea de barra. <br/>            Predeterminado: Superior |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/join/#imathelement) | Une un elemento matemático y forma un bloque matemático |
| [`join(self, math_text)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/join/#str) | Une un texto matemático y forma un bloque matemático |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/divide/#imathelement) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/divide/#str) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`enclose(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/enclose/#) | Encierra un elemento matemático entre paréntesis |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/enclose/#char-char) | Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/function/#imathelement) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/function/#str) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | Toma una función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | Toma una función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | Toma una función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Toma una función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Toma una función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | Crea subíndice |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_subscript/#str) | Crea subíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | Crea superíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_superscript/#str) | Crea superíndice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea subíndice y superíndice a la izquierda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | Crea subíndice y superíndice a la izquierda |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/radical/#imathelement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/radical/#str) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | Toma límite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | Toma límite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | Toma límite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | Toma límite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operador N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | Crea un operador N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | Toma la integral |
| [`integral(self, integral_type)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | Toma la integral sin límites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | Toma la integral |
| [`group(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/group/#) | Coloca este elemento en un grupo usando una llave rizada inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento en un grupo usando un carácter de agrupación, como llave rizada inferior u otro |
| [`to_border_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/to_border_box/#) | Coloca este elemento en un recuadro de borde |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento en un recuadro de borde |
| [`to_math_array(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/to_math_array/#) | Coloca en una matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/accent/#char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [`overbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/overbar/#) | Establece una barra en la parte superior de este elemento |
| [`underbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/underbar/#) | Establece una barra en la parte inferior de este elemento |
| [`to_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/to_box/#) | Coloca este elemento en un recuadro no visual (agrupación lógica) <br/>            que se usa para agrupar componentes de una ecuación u otra instancia de texto matemático.<br/>            Un objeto encajonado puede (por ejemplo) servir como emulador de operador con o sin punto de alineación, <br/>            servir como punto de salto de línea, o agruparse de manera que no permita saltos de línea dentro. |
| [`get_children(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbar/get_children/#) | Obtiene elementos hijos |


### Ver también
* clase [`MathBar`](/slides/python-net/es/aspose.slides.mathtext/mathbar)
* clase [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)