---
title: IMathAccent class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/imathaccent/
---
## IMathAccent class

베이스와 결합 구분 기호로 구성된 억양 기능을 지정합니다.  
예: 𝑎́

IMathAccent 형식은 다음 멤버를 제공합니다:

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/base/) | 억양이 적용된 인수 |
| [`character`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/character/) | 억양 문자<br/>값은 (U+0300–U+036F) 또는 (U+20D0–U+20EF) 범위 내에 있어야 합니다.<br/>기본값: 결합형 삽입 억양 (U+0302) |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/imathaccent/to_box/#) |  |

### See Also
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)