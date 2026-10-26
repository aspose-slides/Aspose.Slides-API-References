---
title: IMathMatrix class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix classe

Especifica o objeto Matrix, que consiste em elementos filho dispostos em uma ou mais linhas e colunas.  
É importante observar que as matrizes não possuem delimitadores incorporados.  
Para colocar a matriz entre colchetes, você deve usar o objeto delimitador (IMathDelimiter).  
Argumentos nulos podem ser usados para criar lacunas nas matrizes.

O tipo IMathMatrix expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`row_count`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/row_count/) | Número de linhas na matriz |
| [`column_count`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/column_count/) | Número de colunas na matriz |
| [`hide_placeholders`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Ocultar os marcadores de posição para elementos de matriz vazios<br/>            Padrão: false |
| [`base_justification`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/base_justification/) | Especifica a justificação vertical em relação ao texto ao redor.<br/>            Valores possíveis são top, bottom, e center.<br/>            Padrão: Center |
| [`min_column_width`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/min_column_width/) | Largura mínima da coluna em twips (1/20 de ponto)<br/>            O espaçamento de lacuna (também referido como “Column Gap” ou “Gap Width”) é adicionado ao <br/>            MinColumnWidth para determinar o espaçamento total da coluna da matriz<br/>            (distância entre as mesmas bordas de diferentes colunas).<br/>            Padrão: 0. |
| [`column_gap_rule`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | O tipo de espaçamento horizontal entre colunas de uma matriz;<br/>            As unidades de espaçamento horizontal podem ser ems ou points (armazenadas como twips).<br/>            Padrão: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/column_gap/) | O valor do espaçamento horizontal entre colunas de uma matriz;<br/>            Se ColumnGapRule estiver definido como 3 ("Exactly"), a unidade será interpretada como twips (1/20 de ponto)<br/>            Se ColumnGapRule estiver definido como 4 ("Multiple"), a unidade será interpretada como número de incrementos de 0,5 em.<br/>            Em outros casos, ignorado.<br/>            Padrão: 0 |
| [`row_gap_rule`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | O tipo de espaçamento vertical entre linhas de uma matriz;<br/>            As unidades de espaçamento vertical podem ser lines ou points (armazenadas como twips).<br/>            Padrão: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/row_gap/) | O valor do espaçamento vertical entre linhas de uma matriz;<br/>            Se RowGapRule estiver definido como 3 ("Exactly"), a unidade será interpretada como twips (1/20 de ponto)<br/>            Se RowGapRule estiver definido como 4 ("Multiple"), a unidade será interpretada como half-lines.<br/>            Padrão: 0 |

## Métodos

| Método | Descrição |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Obter o alinhamento horizontal da coluna especificada |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Definir o alinhamento horizontal da coluna especificada |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Definir o alinhamento horizontal das colunas especificadas |
| [`insert_row_before(self, row_index)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Inserir uma nova linha antes da especificada<br/>            Inicialmente todos os elementos na nova linha são None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Inserir uma nova linha depois da especificada<br/>            Inicialmente todos os elementos na nova linha são None. |
| [`delete_row(self, row_index)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Exclui a linha especificada |
| [`insert_column_before(self, column_index)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Inserir uma nova coluna antes da especificada<br/>            Inicialmente todos os elementos na nova coluna são None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Inserir uma nova coluna depois da especificada<br/>            Inicialmente todos os elementos na nova coluna são None. |
| [`delete_column(self, column_index)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Exclui a coluna especificada |
| [`get_children(self)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/pt/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Veja Também
* módulo [`aspose.slides.mathtext`](/slides/python-net/pt/aspose.slides.mathtext)
* biblioteca [`Aspose.Slides`](/slides/python-net)