---
title: IMathArray class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/imatharray/
---
## IMathArray 클래스

방정식 또는 기타 수학 객체의 수직 배열을 지정합니다.

IMathArray 유형은 다음 멤버를 제공합니다:

## 속성

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/arguments/) |  |
| [`base_justification`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/base_justification/) | 배열이 주변 텍스트에 대해 정렬되는 방식을 지정합니다.<br/>            배열 외부의 텍스트는 배열 객체의 아래쪽, 위쪽 또는 가운데에 정렬될 수 있습니다.<br/>            기본값: Center |
| [`maximum_distribution`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/maximum_distribution/) | 최대 배치<br/>            true인 경우, 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다. |
| [`object_distribution`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/object_distribution/) | 객체 배치<br/>            true인 경우, 배열의 내용은 배열 객체의 최대 너비에 맞게 배치됩니다. |
| [`row_spacing_rule`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/row_spacing_rule/) | 배열 요소 사이의 수직 간격 유형 |
| [`row_spacing`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/row_spacing/) | 배열 행 사이의 간격<br/>            RowSpacingRule이 3 Exactly으로 설정된 경우에만 사용되며, 이 경우 측정 단위는 points입니다.<br/>            또는 Multiple으로 설정된 경우 측정 단위는 half-lines입니다.<br/>            기본값: 0 |

## 메서드

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imatharray/to_box/#) |  |


### 참고
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)