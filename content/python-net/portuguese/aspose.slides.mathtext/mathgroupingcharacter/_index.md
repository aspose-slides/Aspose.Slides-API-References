---
title: MathGroupingCharacter class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter classe

Especifica um símbolo de agrupamento acima ou abaixo de uma expressão, normalmente para destacar a relação entre os elementos

**Herança:**[`MathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)

O tipo MathGroupingCharacter expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Inicializa uma nova instância da classe MathGroupingCharacter <br/>            com o caractere de agrupamento padrão U+23DF (CHAVETA CURVA INFERIOR) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Inicializa uma nova instância da classe MathGroupingCharacter. |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`base`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/base/) | Argumento base |
| [`character`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/character/) | Caractere de Agrupamento<br/>            Valor padrão: U+23DF (CHAVETA CURVA INFERIOR) |
| [`position`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/position/) | Posição do caractere de agrupamento.<br/>            Padrão: Inferior |
| [`vertical_justification`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Justificação vertical do caractere de agrupamento.<br/>            Especifica o alinhamento do objeto em relação à linha de base.<br/>            Por exemplo, quando o caractere de agrupamento está acima do objeto, <br/>            VerticalJustification de Top indica que a parte superior do objeto está na linha de base;<br/>            quando VerticalJustification é definido como Bottom, a parte inferior do objeto está na linha de base<br/>            Padrão: Bottom para Position=Top e Top para Position=Bottom |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Une um elemento matemático e forma um bloco matemático |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Une um texto matemático e forma um bloco matemático |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Envolve um elemento matemático entre parênteses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Recebe uma função de um argumento usando esta instância como nome da função |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Recebe uma função de um argumento usando esta instância como nome da função |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Recebe a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Recebe a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Recebe a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Recebe a função especificada usando esta instância como argumento e um argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Recebe a função especificada usando esta instância como argumento e um argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Cria subscrito |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Cria subscrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Cria sobrescrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Cria sobrescrito |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Cria subscrito e sobrescrito à esquerda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Cria subscrito e sobrescrito à esquerda |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Especifica a raiz matemática do grau fornecido a partir do argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Especifica a raiz matemática do grau fornecido a partir do argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Recebe limite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Recebe limite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Recebe limite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Recebe limite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Cria um operador N-ário |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Cria um operador N-ário |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Recebe a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Recebe a integral |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Recebe a integral sem limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Recebe a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Recebe a integral |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Coloca este elemento em um grupo usando uma chaveta curva inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chaveta curva inferior ou outro |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Coloca este elemento em uma caixa de borda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento em uma caixa de borda |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Insere em um vetor vertical |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Define uma marca de acento (um caractere na parte superior deste elemento) |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Define uma barra na parte superior deste elemento |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Define uma barra na parte inferior deste elemento |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Coloca este elemento em uma caixa não visual (agrupamento lógico) <br/>            que é usada para agrupar componentes de uma equação ou outra instância de texto matemático.<br/>            Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de modo a não permitir quebras de linha dentro. |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Obtém elementos filhos |


### Ver Também
* classe [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)
* classe [`MathGroupingCharacter`](/slides/python-net/pt/aspose.slides.mathtext/mathgroupingcharacter)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)