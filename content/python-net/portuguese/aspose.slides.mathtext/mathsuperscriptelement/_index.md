---
title: MathSuperscriptElement class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement classe

Especifica o objeto sobrescrito, que consiste em uma base 
            e um sobrescrito de tamanho reduzido colocado acima e à direita

**Herança:**[`MathSuperscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement) → [`BaseScript`](/slides/python-net/pt/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)

O tipo MathSuperscriptElement expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, base_arg, super_script)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/__init__/#imathelement-imathelement) | Inicializa uma nova instância da classe MathSuperscriptElement. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`base`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/base/) | Argumento base |
| [`superscript`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/superscript/) | Sobrescrito |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/join/#imathelement) | Une um elemento matemático e forma um bloco matemático |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/join/#str) | Une um texto matemático e forma um bloco matemático |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/divide/#str) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/divide/#str-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/enclose/#) | Envolve um elemento matemático em parênteses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/enclose/#char-char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/function/#imathelement) | Usa uma função de um argumento usando esta instância como nome da função |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/function/#str) | Usa uma função de um argumento usando esta instância como nome da função |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#imathelement) | Usa a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#str) | Usa a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Usa a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Usa a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Usa a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#imathelement) | Cria subscrito |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#str) | Cria subscrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#imathelement) | Cria sobrescrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#str) | Cria sobrescrito |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Cria subscrito e sobrescrito à esquerda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Cria subscrito e sobrescrito à esquerda |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/radical/#imathelement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/radical/#str) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#imathelement) | Define limite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#str) | Define limite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#imathelement) | Define limite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#str) | Define limite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Cria um operador N-ário |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | Cria um operador N-ário |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Calcula a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Calcula a integral |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes) | Calcula a integral sem limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Calcula a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str) | Calcula a integral |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/group/#) | Coloca este elemento em um grupo usando uma chave inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento em um grupo usando um caractere de agrupamento como chave inferior ou outro |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#) | Coloca este elemento em uma caixa de borda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento em uma caixa de borda |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/to_math_array/#) | Coloca em um array vertical |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/accent/#char) | Define um acento (um caractere no topo deste elemento) |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/overbar/#) | Define uma barra no topo deste elemento |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/underbar/#) | Define uma barra na base deste elemento |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/to_box/#) | Coloca este elemento em uma caixa não visual (agrupamento lógico) <br/> que é usada para agrupar componentes de uma equação ou outra instância de texto matemático.<br/> Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, <br/> servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha dentro. |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement/get_children/#) | Obtém elementos filhos |


### Veja também
* classe [`BaseScript`](/slides/python-net/pt/aspose.slides.mathtext/basescript)
* classe [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)
* classe [`MathSuperscriptElement`](/slides/python-net/pt/aspose.slides.mathtext/mathsuperscriptelement)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)