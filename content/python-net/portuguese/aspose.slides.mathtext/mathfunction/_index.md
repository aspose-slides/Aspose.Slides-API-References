---
title: MathFunction class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathfunction/
---
## MathFunction classe

Especifica uma função de um argumento.

**Inheritance:**[`MathFunction`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction) → [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)

O tipo MathFunction expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/__init__/#imathelement-imathelement) | Inicializa uma nova instância da classe MathFunction. |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/__init__/#str-imathelement) | Inicializa uma nova instância da classe MathFunction. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`name`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/name/) | Nome da função<br/>            Por exemplo, nomes de funções são sin e cos |
| [`base`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/base/) | Argumento da Função |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/join/#imathelement) | Une um elemento matemático e forma um bloco matemático |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/join/#str) | Une um texto matemático e forma um bloco matemático |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/divide/#imathelement) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/divide/#str) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/divide/#imathelement-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/divide/#str-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/enclose/#) | Envolve um elemento matemático entre parênteses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/enclose/#char-char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/function/#imathelement) | Obtém uma função de um argumento usando esta instância como nome da função |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/function/#str) | Obtém uma função de um argumento usando esta instância como nome da função |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/as_argument_of_function/#imathelement) | Obtém a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/as_argument_of_function/#str) | Obtém a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsofoneargument) | Obtém a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Obtém a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Obtém a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_subscript/#imathelement) | Cria subscrito |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_subscript/#str) | Cria subscrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_superscript/#imathelement) | Cria sobrescrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_superscript/#str) | Cria sobrescrito |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#str-str) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Cria subscrito e sobrescrito à esquerda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#str-str) | Cria subscrito e sobrescrito à esquerda |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/radical/#imathelement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/radical/#str) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_upper_limit/#imathelement) | Obtém o limite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_upper_limit/#str) | Obtém o limite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_lower_limit/#imathelement) | Obtém o limite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/set_lower_limit/#str) | Obtém o limite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Cria um operador N-ário |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-str-str) | Cria um operador N-ário |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Obtém a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement) | Obtém a integral |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes) | Obtém a integral sem limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Obtém a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str) | Obtém a integral |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/group/#) | Coloca este elemento em um grupo usando uma chave inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave inferior ou outro |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/to_border_box/#) | Coloca este elemento em uma caixa de borda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento em uma caixa de borda |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/to_math_array/#) | Coloca em uma matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/accent/#char) | Define um acento (um caractere no topo deste elemento) |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/overbar/#) | Define uma barra no topo deste elemento |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/underbar/#) | Define uma barra na base deste elemento |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/to_box/#) | Coloca este elemento em uma caixa não visual (agrupamento lógico) <br/>            que é usada para agrupar componentes de uma equação ou outra instância de texto matemático.<br/>            Um objeto encapsulado pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha dentro. |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction/get_children/#) | Obtém elementos filhos |


### Veja Também
* classe [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)
* classe [`MathFunction`](/slides/python-net/pt/aspose.slides.mathtext/mathfunction)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)