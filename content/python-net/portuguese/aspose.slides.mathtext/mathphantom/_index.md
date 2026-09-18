---
title: MathPhantom class
second_title: Referência de API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathphantom/
---
## MathPhantom classe

Representa um objeto matemático fantasma (<m:phant>) que afeta o layout de seu elemento filho sem necessariamente exibi-lo. Um fantasma pode ocultar sua expressão base enquanto preserva sua largura, altura ou profundidade para alinhar fórmulas ou reservar espaço. A visibilidade e o comportamento geométrico são controlados por propriedades como Show, ZeroWid, ZeroAsc, ZeroDesc e Transp.

**Herança:**[`MathPhantom`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)

O tipo MathPhantom expõe os seguintes membros:

## Construtores

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Inicializa uma nova instância da classe [`MathPhantom`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom) <br/>            usando o elemento matemático base especificado. |

## Propriedades

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/base/) | Argumento base |
| [`show`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/show/) | Obtém ou define um valor que indica se o elemento base é exibido. |
| [`zero_width`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/zero_width/) | Obtém ou define um valor que indica se a largura do elemento base <br/>            deve ser tratada como zero. |
| [`zero_asc`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/zero_asc/) | Obtém ou define um valor que indica se a ascensão (altura acima da linha de base) <br/>            do elemento base deve ser tratada como zero. |
| [`zero_desc`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/zero_desc/) | Obtém ou define um valor que indica se a descida (profundidade abaixo da linha de base)<br/>            do elemento base deve ser tratada como zero. |
| [`transp`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/transp/) | Obtém ou define um valor que indica se o fantasma é transparente <br/>            para regras de espaçamento baseadas em classe. |

## Métodos

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/join/#imathelement) | Une um elemento matemático e forma um bloco matemático |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/join/#str) | Une um texto matemático e forma um bloco matemático |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/divide/#str) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/enclose/#) | Envolve um elemento matemático entre parênteses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/function/#imathelement) | Recebe uma função de um argumento usando esta instância como nome da função |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/function/#str) | Recebe uma função de um argumento usando esta instância como nome da função |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Usa a função especificada utilizando esta instância como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Usa a função especificada utilizando esta instância como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Usa a função especificada utilizando esta instância como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Usa a função especificada utilizando esta instância como argumento e argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Usa a função especificada utilizando esta instância como argumento e argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Cria subscrito |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Cria subscrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Cria sobrescrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Cria sobrescrito |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Cria subscrito e sobrescrito à esquerda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Cria subscrito e sobrescrito à esquerda |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/radical/#str) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Obtém limite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Obtém limite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Obtém limite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Obtém limite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Cria um operador N-ário |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Cria um operador N-ário |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Obtém a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Obtém a integral |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Obtém a integral sem limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Obtém a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Obtém a integral |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/group/#) | Coloca este elemento em um grupo usando uma chave curva inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como uma chave curva inferior ou outro |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/to_border_box/#) | Coloca este elemento em uma caixa de borda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento em uma caixa de borda |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/to_math_array/#) | Coloca em uma matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/accent/#char) | Define um acento (um caractere no topo deste elemento) |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/overbar/#) | Define uma barra no topo deste elemento |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/underbar/#) | Define uma barra na parte inferior deste elemento |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/to_box/#) | Coloca este elemento em uma caixa não visual (agrupamento lógico) <br/>            que é usada para agrupar componentes de uma equação ou outra instância de texto matemático.<br/>            Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de modo a não permitir quebras de linha dentro dele. |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom/get_children/#) | Obtém elementos filhos |

### Veja também
* classe [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)
* classe [`MathPhantom`](/slides/python-net/pt/aspose.slides.mathtext/mathphantom)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)