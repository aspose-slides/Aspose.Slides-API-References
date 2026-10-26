---
title: MathBox class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathbox/
---
## MathBox classe

Specifies the logical boxing (packaging) of mathematical element.
            Por exemplo, um objeto encapsulado pode servir como um emulador de operador com ou sem um ponto de alinhamento, 
            servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha internas.
            Por exemplo, o operador "==" deve ser encapsulado para impedir quebras de linha.

**Herança:**[`MathBox`](/slides/python-net/pt/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)

O tipo MathBox expõe os seguintes membros:

## Construtores

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Inicializa MathBox com o elemento especificado como argumento |

## Propriedades

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/base/) | Argumento base |
| [`operator_emulator`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/operator_emulator/) | Emulador de operador.<br/>            Quando verdadeiro, a caixa e seu conteúdo se comportam como um único operador e herdam as propriedades de um operador. <br/>            Isso significa, por exemplo, que o caractere pode servir como ponto de quebra de linha e pode ser alinhado a outros operadores.<br/>            Emuladores de operador são frequentemente usados quando um ou mais glifos se combinam para formar um operador, como '=='.<br/>            Valor padrão: false |
| [`no_break`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/no_break/) | Sem quebra<br/>            Esta propriedade especifica a propriedade "inquebrável" na caixa do objeto. Quando verdadeiro, nenhuma quebra de linha pode ocorrer dentro da caixa.<br/>            Isso pode ser importante para emuladores de operador que consistem em mais de um operador binário. <br/>            Quando este elemento não é especificado, quebras podem ocorrer dentro da caixa.<br/>            Padrão: true |
| [`differential`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/differential/) | Diferencial<br/>            Quando verdadeiro, a caixa atua como um diferencial (por exemplo, 𝑑𝑥 em um integrando), e recebe o espaçamento horizontal apropriado <br/>            para o diferencial matemático.<br/>            Padrão: false |
| [`alignment_point`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/alignment_point/) | Quando verdadeiro, este emulador de operador serve como ponto de alinhamento; isto é, <br/>            pontos de alinhamento designados em outras equações podem ser alinhados a ele.<br/>            Padrão: false |
| [`explicit_break`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/explicit_break/) | Quebra explícita especifica se há uma quebra de linha no início do objeto Box, <br/>            de modo que a linha quebre no início do objeto caixa.<br/>            Especifica o número do operador na linha anterior do texto matemático que deverá<br/>            ser usado como ponto de alinhamento para a linha atual do texto matemático<br/>            valores possíveis: 1..255<br/>            Padrão: 0 (nenhuma quebra explícita) |

## Métodos

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/join/#imathelement) | Une um elemento matemático e forma um bloco matemático |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/join/#str) | Une um texto matemático e forma um bloco matemático |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/divide/#imathelement) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/divide/#str) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/enclose/#) | Envolve um elemento matemático entre parênteses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/enclose/#char-char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/function/#imathelement) | Recebe uma função de um argumento usando esta instância como o nome da função |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/function/#str) | Recebe uma função de um argumento usando esta instância como o nome da função |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Recebe a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Recebe a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Recebe a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Recebe a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Recebe a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Cria subscrito |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_subscript/#str) | Cria subscrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Cria sobrescrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_superscript/#str) | Cria sobrescrito |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Cria subscrito e sobrescrito à esquerda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Cria subscrito e sobrescrito à esquerda |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/radical/#imathelement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/radical/#str) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Recebe limite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Recebe limite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Recebe limite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Recebe limite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Cria um operador N-ário |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Cria um operador N-ário |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Recebe a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Recebe a integral |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Recebe a integral sem limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Recebe a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Recebe a integral |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/group/#) | Coloca este elemento em um grupo usando uma chave curva inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave curva inferior ou outro |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/to_border_box/#) | Coloca este elemento em uma caixa com borda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento em uma caixa com borda |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/to_math_array/#) | Insere em uma matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/accent/#char) | Define um acento (um caractere no topo deste elemento) |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/overbar/#) | Define uma barra no topo deste elemento |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/underbar/#) | Define uma barra na parte inferior deste elemento |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/to_box/#) | Coloca este elemento em uma caixa não visual (agrupamento lógico) <br/>            que é usada para agrupar componentes de uma equação ou outra instância de texto matemático.<br/>            Um objeto encapsulado pode (por exemplo) servir como um emulador de operador com ou sem um ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha internas. |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathbox/get_children/#) | Obter elementos filhos |

### Veja Também
* classe [`MathBox`](/slides/python-net/pt/aspose.slides.mathtext/mathbox)
* classe [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)