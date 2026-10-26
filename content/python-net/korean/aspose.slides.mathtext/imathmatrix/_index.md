---
title: IMathMatrix class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix 클래스

Matrix 객체를 지정하며, 하나 이상의 행 및 열에 배치된 자식 요소로 구성됩니다.  
매트릭스는 내장 구분 기호가 없다는 점에 유의해야 합니다.  
매트릭스를 대괄호 안에 배치하려면 구분 기호 객체(IMathDelimiter)를 사용해야 합니다.  
Null 인수를 사용하면 매트릭스에 빈 공간을 만들 수 있습니다.

IMathMatrix 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`row_count`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/row_count/) | 매트릭스의 행 수 |
| [`column_count`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/column_count/) | 매트릭스의 열 수 |
| [`hide_placeholders`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | 빈 매트릭스 요소에 대한 자리 표시자를 숨깁니다<br/>            Default: false |
| [`base_justification`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/base_justification/) | 주변 텍스트에 대한 수직 정렬을 지정합니다.<br/>            가능한 값은 top, bottom, center 입니다.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/min_column_width/) | twips(포인트의 1/20) 단위의 최소 열 너비<br/>            간격(Gap Spacing, “Column Gap” 또는 “Gap Width”라고도 함)은 MinColumnWidth에 추가되어 전체 매트릭스 열 간격을 결정합니다<br/>            (다른 열의 동일한 가장자리 사이 거리).<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | 매트릭스 열 사이의 수평 간격 유형;<br/>            수평 간격 단위는 em 또는 포인트(twips로 저장)일 수 있습니다.<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/column_gap/) | 매트릭스 열 사이의 수평 간격 값;<br/>            ColumnGapRule이 3("Exactly")으로 설정된 경우, 단위는 twips(포인트의 1/20)로 해석됩니다.<br/>            ColumnGapRule이 4("Multiple")으로 설정된 경우, 단위는 0.5 em 증가분의 개수로 해석됩니다.<br/>            다른 경우는 무시됩니다.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | 매트릭스 행 사이의 수직 간격 유형;<br/>            수직 간격 단위는 라인 또는 포인트(twips로 저장)일 수 있습니다.<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/row_gap/) | 매트릭스 행 사이의 수직 간격 값;<br/>            RowGapRule이 3("Exactly")으로 설정된 경우, 단위는 twips(포인트의 1/20)로 해석됩니다.<br/>            RowGapRule이 4("Multiple")으로 설정된 경우, 단위는 반 라인으로 해석됩니다.<br/>            Default: 0 |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | 지정된 열의 수평 정렬을 가져옵니다 |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | 지정된 열의 수평 정렬을 설정합니다 |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | 지정된 열들의 수평 정렬을 설정합니다 |
| [`insert_row_before(self, row_index)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | 지정된 행 앞에 새 행을 삽입합니다<br/>            새 행의 모든 요소는 처음에 None 입니다. |
| [`insert_row_after(self, row_index)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | 지정된 행 뒤에 새 행을 삽입합니다<br/>            새 행의 모든 요소는 처음에 None 입니다. |
| [`delete_row(self, row_index)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/delete_row/#int) | 지정된 행을 삭제합니다 |
| [`insert_column_before(self, column_index)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | 지정된 열 앞에 새 열을 삽입합니다<br/>            새 열의 모든 요소는 처음에 None 입니다. |
| [`insert_column_after(self, column_index)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | 지정된 열 뒤에 새 열을 삽입합니다<br/>            새 열의 모든 요소는 처음에 None 입니다. |
| [`delete_column(self, column_index)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/delete_column/#int) | 지정된 열을 삭제합니다 |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### 참고
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)