---
title: MathArray class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/matharray/
---
## MathArray 클래스

방정식 또는 모든 수학 객체의 수직 배열을 지정합니다.

**상속:**[`MathArray`](/slides/python-net/ko/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathArray 형식은 다음 멤버를 노출합니다:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/__init__/#imathelement) | 수학 배열을 생성하고 지정된 요소를 그 안에 배치합니다. |
| [`__init__(self, elements)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Properties

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/ko/aspose.slides.mathtext/matharray/arguments/) | 배열의 항목 집합 |
| [`base_justification`](/slides/python-net/ko/aspose.slides.mathtext/matharray/base_justification/) | 배열을 주변 텍스트에 상대적인 정렬을 지정합니다.<br/>            배열 외부 텍스트는 배열 객체의 아래쪽, 위쪽 또는 가운데와 정렬될 수 있습니다.<br/>            기본값: Center |
| [`maximum_distribution`](/slides/python-net/ko/aspose.slides.mathtext/matharray/maximum_distribution/) | Maximum Distribution<br/>            true인 경우, 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 간격을 조정합니다. |
| [`object_distribution`](/slides/python-net/ko/aspose.slides.mathtext/matharray/object_distribution/) | Object Distribution<br/>            true인 경우, 배열 내용은 배열 객체의 최대 너비에 맞게 간격을 조정합니다. |
| [`row_spacing_rule`](/slides/python-net/ko/aspose.slides.mathtext/matharray/row_spacing_rule/) | 배열 요소 간 수직 간격의 유형<br/>            기본값: SingleLineGap |
| [`row_spacing`](/slides/python-net/ko/aspose.slides.mathtext/matharray/row_spacing/) | 배열 행 사이의 간격<br/>            RowSpacingRule이 3 Exactly으로 설정된 경우에만 사용되며, 이 경우 측정 단위는 포인트입니다 <br/>            또는 Multiple인 경우 측정 단위는 절반 라인입니다.<br/>            기본값: 0 |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 형성합니다. |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/join/#str) | 수학 텍스트를 결합하여 수학 블록을 형성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/divide/#imathelement) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/divide/#str) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/enclose/#) | 수학 요소를 괄호로 감쌉니다. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레이밍하여 감쌉니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 함수를 취합니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 함수를 취합니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | 아래 첨자를 생성합니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_subscript/#str) | 아래 첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | 위 첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_superscript/#str) | 위 첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 근을 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 근을 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | 상한을 취합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_upper_limit/#str) | 상한을 취합니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | 하한을 취합니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/set_lower_limit/#str) | 하한을 취합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-항 연산자를 생성합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | N-항 연산자를 생성합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다. |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | 한계 없이 적분을 취합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | 적분을 취합니다. |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/group/#) | 아래 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | 아래 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용하여 이 요소를 그룹에 배치합니다. |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/to_border_box/#) | 이 요소를 테두리 상자에 배치합니다. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 상자에 배치합니다. |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/to_math_array/#) | 수직 배열에 넣습니다. |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/accent/#char) | 강조 표시(이 요소 위에 있는 문자)를 설정합니다. |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/overbar/#) | 이 요소 상단에 바를 설정합니다. |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/underbar/#) | 이 요소 하단에 바를 설정합니다. |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/to_box/#) | 이 요소를 비시각 박스(논리적 그룹)에 배치합니다. <br/>            이는 방정식 구성 요소 또는 다른 수학 텍스트 인스턴스를 그룹화하는 데 사용됩니다.<br/>            박스화된 객체는 (예를 들어) 정렬 지점이 있거나 없을 때 연산자 에뮬레이터로 사용할 수 있으며,<br/>            줄 바꿈 지점으로 사용되거나 내부에서 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/matharray/get_children/#) | 자식 요소를 가져옵니다. |

### 참고
* 클래스 [`MathArray`](/slides/python-net/ko/aspose.slides.mathtext/matharray)
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)