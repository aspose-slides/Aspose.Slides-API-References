---
title: IMathFraction class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/imathfraction/
---
## IMathFraction 클래스

분수 바에 의해 구분된 분자와 분모로 구성된 분수 객체를 지정합니다.
분수 바는 분수 속성에 따라 가로형 또는 대각선형이 될 수 있습니다.
분수 객체는 분수 바 없이 한 요소를 다른 요소 위에 배치하는 스택 함수도 나타내는 데 사용됩니다.

IMathFraction 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`fraction_type`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/fraction_type/) | Fraction type<br/>            Default: Bar |
| [`numerator`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/numerator/) | Numerator |
| [`denominator`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/denominator/) | Denominator |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathfraction/to_box/#) |  |

### 참조
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)