---
title: MathBar class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathbar/
---
## MathBar classe

Especifica a função barra, consistindo de um argumento base e uma barra superior ou inferior

**Inheritance:**[`MathBar`](/slides/python-net/pt/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)

O tipo MathBar expõe os seguintes membros:

## Construtores

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/__init__/#imathelement) | Inicializa MathBar com barra superior (Posição superior) |
| [`__init__(self, element, position)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | Inicializa MathBar com posição especificada |

## Propriedades

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/base/) | Argumento base |
| [`position`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/position/) | Posição da linha da barra. <br/>            Padrão: Superior |

## Métodos

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/join/#imathelement) | Une um elemento matemático e forma um bloco matemático |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/join/#str) | Une um texto matemático e forma um bloco matemático |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/divide/#imathelement) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/divide/#str) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/enclose/#) | Envolve um elemento matemático em parênteses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/enclose/#char-char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/function/#imathelement) | Obtém uma função de um argumento usando esta instância como nome da função |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/function/#str) | Obtém uma função de um argumento usando esta instância como nome da função |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | Obtém a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | Obtém a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | Obtém a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Obtém a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Obtém a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | Cria subscrito |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_subscript/#str) | Cria subscrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | Cria sobrescrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_superscript/#str) | Cria sobrescrito |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | Cria subscrito e sobrescrito à esquerda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | Cria subscrito e sobrescrito à esquerda |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/radical/#imathelement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/radical/#str) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | Obtém limite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | Obtém limite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | Obtém limite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | Obtém limite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | Cria um operador N-ário |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | Cria um operador N-ário |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Obtém a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | Obtém a integral |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | Obtém a integral sem limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | Obtém a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | Obtém a integral |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/group/#) | Coloca este elemento em um grupo usando uma chave inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave inferior ou outro |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/to_border_box/#) | Coloca este elemento em uma caixa de borda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento em uma caixa de borda |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/to_math_array/#) | Insere em uma matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/accent/#char) | Define uma marca de acento (um caractere no topo deste elemento) |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/overbar/#) | Define uma barra no topo deste elemento |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/underbar/#) | Define uma barra na parte inferior deste elemento |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/to_box/#) | Coloca este elemento em uma caixa não visual (agrupamento lógico) <br/>            que é usada para agrupar componentes de uma equação ou outra instância de texto matemático.<br/>            Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha dentro. |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbar/get_children/#) | Obtém elementos filhos |


### Veja Também
* classe [`MathBar`](/slides/python-net/pt/aspose.slides.mathtext/mathbar)
* classe [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)