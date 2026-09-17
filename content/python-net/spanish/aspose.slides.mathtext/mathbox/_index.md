---
title: MathBox class
second_title: Referencia API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.mathtext/mathbox/
---
## Clase MathBox

Especifica el empaquetado lógico (cajado) del elemento matemático.
    Por ejemplo, un objeto en caja puede servir como un emulador de operador con o sin un punto de alineación,
    servir como un punto de salto de línea, o agruparse de manera que no se permitan saltos de línea dentro.
    Por ejemplo, el operador "==" debe estar en caja para evitar saltos de línea.

**Herencia:**[`MathBox`](/slides/python-net/es/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)

El tipo MathBox expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Inicializa MathBox con el elemento especificado como argumento |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`base`](/slides/python-net/es/aspose.slides.mathtext/mathbox/base/) | Argumento base |
| [`operator_emulator`](/slides/python-net/es/aspose.slides.mathtext/mathbox/operator_emulator/) | Emulador de operador.<br/> Cuando sea verdadero, la caja y su contenido se comportan como un solo operador y heredan las propiedades de un operador.<br/> Esto significa, por ejemplo, que el carácter puede servir como punto de salto de línea y puede alinearse con otros operadores.<br/> Los emuladores de operadores se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='.<br/> Valor predeterminado: false |
| [`no_break`](/slides/python-net/es/aspose.slides.mathtext/mathbox/no_break/) | Sin salto<br/> Esta propiedad especifica la propiedad "ininterrumpible" en la caja del objeto. Cuando sea verdadera, no pueden ocurrir saltos de línea dentro de la caja.<br/> Esto puede ser importante para los emuladores de operadores que constan de más de un operador binario.<br/> Cuando este elemento no se especifica, pueden producirse saltos dentro de la caja.<br/> Valor predeterminado: true |
| [`differential`](/slides/python-net/es/aspose.slides.mathtext/mathbox/differential/) | Diferencial<br/> Cuando sea verdadero, la caja actúa como un diferencial (p. ej., 𝑑𝑥 en un integrando) y recibe el espaciado horizontal apropiado para el diferencial matemático.<br/> Valor predeterminado: false |
| [`alignment_point`](/slides/python-net/es/aspose.slides.mathtext/mathbox/alignment_point/) | Cuando sea verdadero, este emulador de operador sirve como un punto de alineación; es decir,<br/> los puntos de alineación designados en otras ecuaciones pueden alinearse con él.<br/> Valor predeterminado: false |
| [`explicit_break`](/slides/python-net/es/aspose.slides.mathtext/mathbox/explicit_break/) | Salto explícito especifica si hay un salto de línea al inicio del objeto Box,<br/> de modo que la línea se envuelva al inicio del objeto box.<br/> Especifica el número del operador en la línea anterior de texto matemático que deberá usarse como punto de alineación para la línea actual de texto matemático<br/> valores posibles: 1..255<br/> Valor predeterminado: 0 (sin salto explícito) |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/join/#imathelement) | Une un elemento matemático y forma un bloque matemático |
| [`join(self, math_text)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/join/#str) | Une un texto matemático y forma un bloque matemático |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/divide/#imathelement) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/divide/#str) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`enclose(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/enclose/#) | Encierra un elemento matemático entre paréntesis |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/enclose/#char-char) | Encierra un elemento matemático en los caracteres especificados, como paréntesis u otros caracteres como marco |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/function/#imathelement) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/function/#str) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Toma la función especificada usando esta instancia como argumento y un argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Crea subíndice |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_subscript/#str) | Crea subíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Crea superíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_superscript/#str) | Crea superíndice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea subíndice y superíndice a la izquierda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Crea subíndice y superíndice a la izquierda |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/radical/#imathelement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/radical/#str) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Toma límite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Toma límite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Toma límite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Toma límite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operador N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Crea un operador N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Toma la integral |
| [`integral(self, integral_type)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Toma la integral sin límites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Toma la integral |
| [`group(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/group/#) | Coloca este elemento en un grupo usando una llave curva inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento en un grupo usando un carácter de agrupación, como una llave curva inferior u otro |
| [`to_border_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/to_border_box/#) | Coloca este elemento en un cuadro con borde |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento en un cuadro con borde |
| [`to_math_array(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/to_math_array/#) | Coloca en una matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/accent/#char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [`overbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/overbar/#) | Establece una barra en la parte superior de este elemento |
| [`underbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/underbar/#) | Establece una barra en la parte inferior de este elemento |
| [`to_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/to_box/#) | Coloca este elemento en una caja no visual (agrupación lógica)<br/> que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático.<br/> Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación,<br/> servir como punto de salto de línea, o agruparse de manera que no se permitan saltos de línea dentro. |
| [`get_children(self)`](/slides/python-net/es/aspose.slides.mathtext/mathbox/get_children/#) | Obtiene los elementos hijos |

### Ver también
* clase [`MathBox`](/slides/python-net/es/aspose.slides.mathtext/mathbox)
* clase [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)