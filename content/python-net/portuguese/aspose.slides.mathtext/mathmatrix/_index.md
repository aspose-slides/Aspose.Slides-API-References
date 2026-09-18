---
title: MathMatrix class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix classe

Especifica o objeto Matrix, composto por elementos filhos dispostos em uma ou mais linhas e colunas. 
            É importante observar que as matrizes não têm delimitadores incorporados. 
            Para colocar a matriz entre colchetes, você deve usar o objeto delimitador (IMathDelimiter).
            Argumentos nulos podem ser usados para criar espaços nas matrizes.

**Herança:**[`MathMatrix`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)

O tipo MathMatrix expõe os seguintes membros:

## Construtores

| Constructor | Description |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Inicializa uma nova instância da classe MathMatrix. |

## Propriedades

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/row_count/) | Número de linhas na matriz |
| [`column_count`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/column_count/) | Número de colunas na matriz |
| [`hide_placeholders`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Oculta os marcadores de posição para elementos vazios da matriz<br/>            Padrão: false |
| [`base_justification`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/base_justification/) | Especifica a justificação vertical em relação ao texto circundante. <br/>            Valores possíveis são top, bottom, e center.<br/>            Padrão: Center |
| [`min_column_width`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/min_column_width/) | Largura mínima da coluna em twips (1/20 de um ponto)<br/>            O espaçamento de lacuna (também referido como “Column Gap” ou “Gap Width”) é adicionado ao <br/>            MinColumnWidth para determinar o espaçamento total da coluna da Matriz<br/>            (distância entre as mesmas bordas de colunas diferentes).<br/>            Padrão: 0. |
| [`column_gap_rule`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | O tipo de espaçamento horizontal entre colunas de uma matriz; <br/>            As unidades de espaçamento horizontal podem ser ems ou pontos (armazenados como twips).<br/>            Padrão: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/column_gap/) | O valor do espaçamento horizontal entre colunas de uma matriz;<br/>            Se o ColumnGapRule estiver definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de um ponto)<br/>            Se o ColumnGapRule estiver definido como 4 ("Multiple"), a unidade é interpretada como número de incrementos de 0,5 em.<br/>            Em outros casos, ignorado.<br/>            Padrão: 0 |
| [`row_gap_rule`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | O tipo de espaçamento vertical entre linhas de uma matriz; <br/>            As unidades de espaçamento vertical podem ser linhas ou pontos (armazenados como twips).<br/>            Padrão: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/row_gap/) | O valor do espaçamento vertical entre linhas de uma matriz;<br/>            Se o RowGapRule estiver definido como 3 ("Exactly"), a unidade é interpretada como twips (1/20 de um ponto)<br/>            Se o RowGapRule estiver definido como 4 ("Multiple"), a unidade é interpretada como meia linha.<br/>            Padrão: 0 |

## Métodos

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Une um elemento matemático e forma um bloco matemático |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/join/#str) | Une um texto matemático e forma um bloco matemático |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/divide/#str) | Cria uma fração com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/enclose/#) | Envolve um elemento matemático entre parênteses |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Recebe uma função de um argumento usando esta instância como nome da função |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/function/#str) | Recebe uma função de um argumento usando esta instância como nome da função |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Recebe a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Recebe a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Recebe a função especificada usando esta instância como argumento |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Recebe a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Recebe a função especificada usando esta instância como argumento e argumento adicional especificado |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Cria subíndice |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Cria subíndice |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Cria sobrescrito |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Cria sobrescrito |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Cria subíndice e sobrescrito à direita |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Cria subíndice e sobrescrito à direita |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Cria subíndice e sobrescrito à esquerda |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Cria subíndice e sobrescrito à esquerda |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Especifica a raiz matemática do grau fornecido a partir do argumento especificado. |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/radical/#str) | Especifica a raiz matemática do grau fornecido a partir do argumento especificado. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Recebe limite superior |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Recebe limite superior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Recebe limite inferior |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Recebe limite inferior |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Cria um operador N-ário |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Cria um operador N-ário |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Recebe a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Recebe a integral |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Recebe a integral sem limites |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Recebe a integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Recebe a integral |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/group/#) | Coloca este elemento em um grupo usando uma chave inferior |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave inferior ou outro |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Coloca este elemento em uma caixa de borda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Coloca este elemento em uma caixa de borda |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Coloca em uma matriz vertical |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/accent/#char) | Define um acento (um caractere acima deste elemento) |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/overbar/#) | Define uma barra no topo deste elemento |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/underbar/#) | Define uma barra na base deste elemento |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/to_box/#) | Coloca este elemento em uma caixa não visual (agrupamento lógico) <br/>            que é usada para agrupar componentes de uma equação ou outra instância de texto matemático.<br/>            Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem um ponto de alinhamento, <br/>            servir como ponto de quebra de linha, ou ser agrupado de forma a não permitir quebras de linha dentro. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Obtém o alinhamento horizontal da coluna especificada |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Define o alinhamento horizontal da coluna especificada |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Define o alinhamento horizontal das colunas especificadas |
| [`insert_row_before(self, row_index)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Insere uma nova linha antes da especificada<br/>            Inicialmente todos os elementos na nova linha são None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Insere uma nova linha após a especificada<br/>            Inicialmente todos os elementos na nova linha são None. |
| [`delete_row(self, row_index)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Exclui a linha especificada |
| [`insert_column_before(self, column_index)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Insere uma nova coluna antes da especificada<br/>            Inicialmente todos os elementos na nova coluna são None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Insere uma nova coluna após a especificada<br/>            Inicialmente todos os elementos na nova coluna são None. |
| [`delete_column(self, column_index)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Exclui a coluna especificada |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix/get_children/#) | Obtém elementos filhos |


### Veja Também
* classe [`MathElementBase`](/slides/python-net/pt/aspose.slides.mathtext/mathelementbase)
* classe [`MathMatrix`](/slides/python-net/pt/aspose.slides.mathtext/mathmatrix)
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)