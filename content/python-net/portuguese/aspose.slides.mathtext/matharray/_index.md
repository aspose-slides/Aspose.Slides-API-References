---
title: MathArray class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.mathtext/matharray/
---
## MathArray classe

Specifica um array vertical de equações ou quaisquer objetos matemáticos

**Inheritance:**[`MathArray`](/slides/python-net/pt/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)

The MathArray type exposes the following members:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/__init__/#imathelement) | Cria um array matemático e coloca o elemento especificado nele |
| [`__init__(self, elements)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`arguments`](/slides/python-net/pt/aspose.slides.mathtext/matharray/arguments/) | O conjunto de itens do array |
| [`base_justification`](/slides/python-net/pt/aspose.slides.mathtext/matharray/base_justification/) | Especifica o alinhamento do array em relação ao texto ao redor<br/>            Texto fora do array pode ser alinhado com a parte inferior, superior ou central de um objeto array.<br/>            Valor padrão: Center |
| [`maximum_distribution`](/slides/python-net/pt/aspose.slides.mathtext/matharray/maximum_distribution/) | Distribuição Máxima<br/>            Quando verdadeiro, o array é espaçado até a largura máxima do elemento contêiner (página, coluna, célula, etc.). |
| [`object_distribution`](/slides/python-net/pt/aspose.slides.mathtext/matharray/object_distribution/) | Distribuição de Objeto<br/>            Quando verdadeiro, o conteúdo do array é espaçado até a largura máxima do objeto array. |
| [`row_spacing_rule`](/slides/python-net/pt/aspose.slides.mathtext/matharray/row_spacing_rule/) | O tipo de espaçamento vertical entre os elementos do array<br/>            Padrão: SingleLineGap |
| [`row_spacing`](/slides/python-net/pt/aspose.slides.mathtext/matharray/row_spacing/) | Espaçamento entre linhas de um array<br/>            É usado somente quando RowSpacingRule está definido como 3 Exactly, caso em que a unidade de medida é pontos <br/>            ou Multiple, caso em que a unidade de medida é meia linha.<br/>            Padrão: 0 |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/join/#imathelement) | Une um elemento matemático e forma um bloco matemático |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/join/#str) | Une um texto matemático e forma um bloco matemático |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/divide/#imathelement) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/divide/#str) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/enclose/#) | Envolve um elemento matemático entre parênteses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/enclose/#char-char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/function/#imathelement) | Define uma função de um argumento usando esta instância como nome da função |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/function/#str) | Define uma função de um argumento usando esta instância como nome da função |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Define a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Define a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Define a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Define a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Define a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Cria subscrito |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_subscript/#str) | Cria subscrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Cria sobrescrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_superscript/#str) | Cria sobrescrito |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Cria subscrito e sobrescrito à esquerda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Cria subscrito e sobrescrito à esquerda |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/radical/#imathelement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/radical/#str) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Define limite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Define limite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Define limite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Define limite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Cria um operador N-ário |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Cria um operador N-ário |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Define a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Define a integral |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Define a integral sem limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Define a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Define a integral |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/group/#) | Coloca este elemento em um grupo usando uma chave inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento em um grupo usando um caractere de agrupamento como chave inferior ou outro |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/to_border_box/#) | Coloca este elemento em uma caixa de borda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento em uma caixa de borda |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/to_math_array/#) | Insere em um array vertical |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/accent/#char) | Define um acento (um caractere na parte superior deste elemento) |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/overbar/#) | Define uma barra na parte superior deste elemento |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/underbar/#) | Define uma barra na parte inferior deste elemento |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/to_box/#) | Coloca este elemento em uma caixa não visual (agrupamento lógico) <br/>            que é usada para agrupar componentes de uma equação ou outra instância de texto matemático.<br/>            Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de modo a não permitir quebras de linha dentro. |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/matharray/get_children/#) | Obtém elementos filhos |


### Veja Também
* classe [`MathArray`](/slides/python-net/pt/aspose.slides.mathtext/matharray)
* classe [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)