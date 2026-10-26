---
title: MathMatrix class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix 클래스

하나 이상의 행과 열에 배치된 자식 요소로 구성된 Matrix 객체를 지정합니다.  
It is important to note that matrices do not have built in delimiters.  
To place the matrix in the brackets you should use the delimiter object (IMathDelimiter).  
Null arguments can be used to create gaps in matrices.

**상속:**[`MathMatrix`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathMatrix 유형은 다음 멤버를 노출합니다:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | MathMatrix 클래스의 새 인스턴스를 초기화합니다. |

## Properties

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/row_count/) | 행렬의 행 수 |
| [`column_count`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/column_count/) | 행렬의 열 수 |
| [`hide_placeholders`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | 빈 행렬 요소에 대한 자리 표시자를 숨깁니다<br/>            Default: false |
| [`base_justification`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/base_justification/) | 주변 텍스트에 대한 수직 정렬을 지정합니다. <br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/min_column_width/) | twips(포인트의 1/20) 단위로 최소 열 너비<br/>            ‘Column Gap’ 또는 ‘Gap Width’라고도 하는 간격이 MinColumnWidth에 추가되어 전체 Matrix Column Spacing(다른 열의 동일한 가장자리 사이 거리)을 결정합니다.<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | 행렬의 열 사이 수평 간격 유형; <br/>            Horizontal spacing units can be ems or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/column_gap/) | 행렬의 열 사이 수평 간격 값;<br/>            If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments.<br/>            In other cases ignored.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | 행렬의 행 사이 수직 간격 유형; <br/>            Vertical spacing units can be lines or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/row_gap/) | 행렬의 행 사이 수직 간격 값;<br/>            If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines.<br/>            Default: 0 |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 만듭니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/join/#str) | 수학 텍스트를 결합하여 수학 블록을 만듭니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/divide/#str) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/enclose/#) | 수학 요소를 괄호로 둘러씁니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸 프레임을 만듭니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수를 함수 형태로 취합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수를 함수 형태로 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 취합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | 첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | 첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | 위첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 첨자와 위첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 근을 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 근을 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | 상한을 취합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | 상한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | 하한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | 하한을 취합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | 제한 없는 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | 적분을 취합니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/group/#) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/to_border_box/#) | 이 요소를 경계 상자에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 경계 상자에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/to_math_array/#) | 수직 배열에 삽입합니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/accent/#char) | 강세 표시(이 요소 위의 문자)를 설정합니다 |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/overbar/#) | 이 요소 상단에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/underbar/#) | 이 요소 하단에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/to_box/#) | 이 요소를 비시각 박스(논리적 그룹화)에 배치합니다 <br/>            이는 방정식 또는 다른 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스 객체는 (예를 들어) 정렬 지점이 있거나 없거나 연산자 에뮬레이터 역할을 할 수 있으며,<br/>            줄 바꿈 지점으로 사용되거나 내부에서 줄 바꿈을 허용하지 않는 방식으로 그룹화될 수 있습니다. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | 지정된 열의 수평 정렬을 가져옵니다 |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | 지정된 열의 수평 정렬을 설정합니다 |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | 지정된 열들의 수평 정렬을 설정합니다 |
| [`insert_row_before(self, row_index)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | 지정된 행 앞에 새 행을 삽입합니다<br/>            새 행의 모든 요소는 처음에 None입니다. |
| [`insert_row_after(self, row_index)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | 지정된 행 뒤에 새 행을 삽입합니다<br/>            새 행의 모든 요소는 처음에 None입니다. |
| [`delete_row(self, row_index)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/delete_row/#int) | 지정된 행을 삭제합니다 |
| [`insert_column_before(self, column_index)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | 지정된 열 앞에 새 열을 삽입합니다<br/>            새 열의 모든 요소는 처음에 None입니다. |
| [`insert_column_after(self, column_index)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | 지정된 열 뒤에 새 열을 삽입합니다<br/>            새 열의 모든 요소는 처음에 None입니다. |
| [`delete_column(self, column_index)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/delete_column/#int) | 지정된 열을 삭제합니다 |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix/get_children/#) | 자식 요소를 가져옵니다 |


### See Also
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 클래스 [`MathMatrix`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)