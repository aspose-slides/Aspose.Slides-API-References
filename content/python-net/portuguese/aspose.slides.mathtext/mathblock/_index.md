---
title: MathBlock class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathblock/
---
## MathBlock classe

Especifica uma instância de texto matemático que está contida dentro de um MathParagraph e começa em sua própria linha.
Todas as zonas de matemática, incluindo equações, expressões, matrizes de equações ou expressões e fórmulas são representadas por um bloco matemático.

**Herança:**[`MathBlock`](/slides/python-net/pt/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)

O tipo MathBlock expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/__init__/#) | Inicializa uma nova instância da classe MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Cria um novo bloco matemático e coloca o elemento especificado nele |
| [`__init__(self, math_elements)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`count`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/count/) | Obtém o número de elementos matemáticos filhos realmente contidos na coleção.<br/>            Somente leitura **int**. |
| [`is_read_only`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/is_read_only/) | Retorna false porque a coleção de elementos filhos pode ser modificada. |

Obtém ou define IMathElement no índice especificado.

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/__getitem__/) | O índice baseado em zero do item |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/join/#imathelement) | Une um elemento matemático a este bloco matemático |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/join/#str) | Une um texto matemático a este bloco matemático |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/divide/#imathelement) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/divide/#str) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/enclose/#char-char) | Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros caracteres como enquadramento |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Envolve os elementos filhos deste bloco em caracteres especificados, como parênteses ou outros como enquadramento<br/>            e delimita com um caractere separador |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/enclose/#) | Envolve um elemento matemático em parênteses |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/function/#imathelement) | Obtém uma função de um argumento usando esta instância como nome da função |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/function/#str) | Obtém uma função de um argumento usando esta instância como nome da função |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Obtém a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Obtém a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Obtém a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Obtém a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Obtém a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Cria subscrito |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_subscript/#str) | Cria subscrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Cria sobrescrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_superscript/#str) | Cria sobrescrito |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Cria subscrito e sobrescrito à direita |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Cria subscrito e sobrescrito à esquerda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Cria subscrito e sobrescrito à esquerda |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/radical/#imathelement) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/radical/#str) | Especifica a raiz matemática do grau dado a partir do argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Obtém limite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Obtém limite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Obtém limite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Obtém limite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Cria um operador N-ário |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Cria um operador N-ário |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Obtém a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Obtém a integral |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Obtém a integral sem limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Obtém a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Obtém a integral |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/group/#) | Coloca este elemento em um grupo usando uma chave inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave inferior ou outro |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/to_border_box/#) | Coloca este elemento em uma caixa de borda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento em uma caixa de borda |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/to_math_array/#) | Coloca elementos filhos em uma matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/accent/#char) | Define uma marca de acento (um caractere no topo deste elemento) |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/overbar/#) | Define uma barra no topo deste elemento |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/underbar/#) | Define uma barra na base deste elemento |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/to_box/#) | Coloca este elemento em uma caixa não visual (agrupamento lógico) <br/>            que é usada para agrupar componentes de uma equação ou outra instância de texto matemático.<br/>            Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de modo a não permitir quebras de linha dentro. |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/get_children/#) | Obtém elementos filhos |
| [`add(self, item)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/add/#imathelement) | Adiciona um elemento matemático ao final da coleção. |
| [`clear(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/clear/#) | Remove todos os elementos da coleção. |
| [`contains(self, item)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/contains/#imathelement) | Determina se a coleção contém um valor específico. |
| [`copy_to(self, array, array_index)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Copia para a matriz especificada. |
| [`remove(self, item)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/remove/#imathelement) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [`index_of(self, item)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Determina o índice de um elemento matemático específico na coleção. |
| [`insert(self, index, item)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Insere um MathElement na coleção no índice especificado. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/remove_at/#int) | Remove o elemento no índice especificado da coleção. |
| [`join_block(self, other)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Une outro bloco matemático a este. |
| [`delimit(self, separator_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/delimit/#char) | Delimina os elementos filhos com caractere separador (sem os colchetes) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/pt/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Salva o conteúdo deste [`MathBlock`](/slides/python-net/pt/aspose.slides.mathtext/mathblock) como MathML |

### Ver Também
* classe [`MathBlock`](/slides/python-net/pt/aspose.slides.mathtext/mathblock)
* classe [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)