---
title: MathGroupingCharacter class
second_title: Aspose.Slides para Python via .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter clase

Especifica un símbolo de agrupación por encima o por debajo de una expresión, generalmente para resaltar la relación entre los elementos

**Herencia:**[`MathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)

El tipo MathGroupingCharacter expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Inicializa una nueva instancia de la clase MathGroupingCharacter <br/>            con el carácter de agrupación predeterminado U+23DF (LLAVE CURVA INFERIOR) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Inicializa una nueva instancia de la clase MathGroupingCharacter. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`base`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/base/) | Argumento base |
| [`character`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/character/) | Carácter de agrupación<br/>            Valor predeterminado: U+23DF (LLAVE CURVA INFERIOR) |
| [`position`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/position/) | Posición del carácter de agrupación.<br/>            Predeterminado: Inferior |
| [`vertical_justification`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Justificación vertical del carácter de grupo.<br/>            Especifica la alineación del objeto respecto a la línea base.<br/>            Por ejemplo, cuando el carácter de grupo está por encima del objeto, <br/>            VerticalJustification de Top indica que la parte superior del objeto está en la línea base;<br/>            cuando VerticalJustification está configurado en Bottom, la parte inferior del objeto está en la línea base<br/>            Predeterminado: Bottom para Position=Top, y Top para Position=Bottom |

## Métodos

| Método | Descripción |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Une un elemento matemático y forma un bloque matemático |
| [`join(self, math_text)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Une un texto matemático y forma un bloque matemático |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Crea una fracción con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Crea una fracción del tipo especificado con este numerador y el denominador especificado |
| [`enclose(self)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Encierra un elemento matemático entre paréntesis |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`function(self, function_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Toma una función de un argumento usando esta instancia como nombre de la función |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Toma la función especificada usando esta instancia como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Crea subíndice |
| [`set_subscript(self, subscript)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Crea subíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Crea superíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Crea superíndice |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Crea subíndice y superíndice a la derecha |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Crea subíndice y superíndice a la izquierda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Crea subíndice y superíndice a la izquierda |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Especifica la raíz matemática del grado dado a partir del argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Toma límite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Toma límite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Toma límite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Toma límite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Crea un operador N-ario |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Crea un operador N-ario |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Toma la integral |
| [`integral(self, integral_type)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Toma la integral sin límites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Toma la integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Toma la integral |
| [`group(self)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Coloca este elemento en un grupo usando una llave curva inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento en un grupo usando un carácter de agrupación como llave curva inferior u otro |
| [`to_border_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Coloca este elemento en una caja con borde |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento en una caja con borde |
| [`to_math_array(self)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Inserta en una matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Establece una marca de acento (un carácter en la parte superior de este elemento) |
| [`overbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Establece una barra en la parte superior de este elemento |
| [`underbar(self)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Establece una barra en la parte inferior de este elemento |
| [`to_box(self)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Coloca este elemento en una caja no visual (agrupación lógica) <br/>            que se utiliza para agrupar componentes de una ecuación u otra instancia de texto matemático.<br/>            Un objeto en caja puede (por ejemplo) servir como un emulador de operador con o sin un punto de alineación, <br/>            servir como punto de salto de línea, o agruparse de manera que no se permitan saltos de línea dentro. |
| [`get_children(self)`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Obtiene los elementos hijos |

### Ver también
* clase [`MathElementBase`](/slides/python-net/es/aspose.slides.mathtext/mathelementbase)
* clase [`MathGroupingCharacter`](/slides/python-net/es/aspose.slides.mathtext/mathgroupingcharacter)
* módulo [`aspose.slides.mathtext`](/slides/python-net/es/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)