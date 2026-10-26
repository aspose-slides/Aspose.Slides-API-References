---
title: BaseScript class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/basescript/
---
## BaseScript 클래스

수학 스크립트

**Inheritance:**[`BaseScript`](/slides/python-net/ko/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

BaseScript 타입은 다음 멤버를 제공합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/basescript/base/) | 기본 인수 |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/join/#imathelement) | 수학 요소를 연결하여 수학 블록을 만듭니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/join/#str) | 수학 텍스트를 연결하여 수학 블록을 만듭니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/divide/#imathelement) | 지정된 분모와 이 분자를 사용해 분수를 만듭니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/divide/#str) | 지정된 분모와 이 분자를 사용해 분수를 만듭니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 만듭니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 만듭니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/enclose/#) | 수학 요소를 괄호로 둘러씁니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자나 다른 문자로 둘러싸서 프레임을 만듭니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로, 지정된 추가 인수를 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로, 지정된 추가 인수를 사용하여 지정된 함수를 취합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_subscript/#imathelement) | 아래첨자를 만듭니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_subscript/#str) | 아래첨자를 만듭니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_superscript/#imathelement) | 위첨자를 만듭니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_superscript/#str) | 위첨자를 만듭니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 만듭니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 만듭니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 만듭니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 만듭니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 제곱근을 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 제곱근을 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_upper_limit/#imathelement) | 상한을 취합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_upper_limit/#str) | 상한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_lower_limit/#imathelement) | 하한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/set_lower_limit/#str) | 하한을 취합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 만듭니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 만듭니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/integral/#mathintegraltypes) | 한계 없이 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-str-str) | 적분을 취합니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/group/#) | 하단 중괄호를 사용해 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용해 이 요소를 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/to_border_box/#) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/to_math_array/#) | 수직 배열에 배치합니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/accent/#char) | 이 요소 위에 악센트 표시(문자)를 설정합니다 |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/overbar/#) | 이 요소 위에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/underbar/#) | 이 요소 아래에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/to_box/#) | 이 요소를 비시각적 상자(논리적 그룹화) 안에 배치합니다 <br/>            이는 방정식 또는 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스 객체는 (예를 들어) 정렬점을 사용하거나 사용하지 않는 연산자 에뮬레이터로 작동할 수 있으며,<br/>            줄 바꿈 지점으로 작동하거나 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/basescript/get_children/#) |  |

### 참고
* 클래스 [`BaseScript`](/slides/python-net/ko/aspose.slides.mathtext/basescript)
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)