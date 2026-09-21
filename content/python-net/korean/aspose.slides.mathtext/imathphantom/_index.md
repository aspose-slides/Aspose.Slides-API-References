---
title: IMathPhantom class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/imathphantom/
---
## IMathPhantom 클래스

팬텀 수학 객체 (<m:phant>)를 나타내며, 자식 요소의 레이아웃에 영향을 주지만 반드시 표시될 필요는 없습니다. 팬텀은 기본 식을 숨기면서도 너비, 높이 또는 깊이를 유지하여 수식을 정렬하거나 공간을 예약할 수 있습니다. 가시성 및 기하학 동작은 Show, ZeroWid, ZeroAsc, ZeroDesc 및 Transp와 같은 속성으로 제어됩니다.

The IMathPhantom type exposes the following members:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/base/) | 기본 인수 |
| [`show`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/show/) | 기본 요소가 표시되는지를 나타내는 값을 가져오거나 설정합니다. |
| [`zero_width`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/zero_width/) | 기본 요소의 너비가 <br/> 0으로 간주되어야 하는지를 나타내는 값을 가져오거나 설정합니다. |
| [`zero_asc`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/zero_asc/) | 기본 요소의 상승(기준선 위의 높이)이 <br/> 0으로 간주되어야 하는지를 나타내는 값을 가져오거나 설정합니다. |
| [`zero_desc`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/zero_desc/) | 기본 요소의 하강(기준선 아래의 깊이)이 <br/> 0으로 간주되어야 하는지를 나타내는 값을 가져오거나 설정합니다. |
| [`transp`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/transp/) | 클래스 기반 간격 규칙에 대해 팬텀이 투명한지를 <br/> 나타내는 값을 가져오거나 설정합니다. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathphantom/to_box/#) |  |

### 참고
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)