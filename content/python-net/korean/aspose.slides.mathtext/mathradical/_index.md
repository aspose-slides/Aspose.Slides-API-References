---
title: MathRadical class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathradical/
---
## MathRadical 클래스

기본(base)과 선택적 차수(degree)로 구성된 루트 함수를 지정합니다.
            루트 객체의 예는 √𝑥입니다.

**상속:**[`MathRadical`](/slides/python-net/ko/aspose.slides.mathtext/mathradical) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathRadical 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, base_argument, degree_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/__init__/#imathelement-imathelement) | MathRadical 클래스를 새 인스턴스로 초기화합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/base/) | 기본 인수 |
| [`degree`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/degree/) | 차수 인수 |
| [`hide_degree`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/hide_degree/) | 차수 숨기기<br/>            true이면 차수가 표시되지 않습니다, 예: √𝑥 |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/join/#str) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/divide/#imathelement) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/divide/#str) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분자를 이 분자와 지정된 분모로 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/divide/#str-mathfractiontypes) | 지정된 유형의 분자를 이 분자와 지정된 분모로 생성합니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/enclose/#) | 수학 요소를 괄호로 감쌉니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/enclose/#char-char) | 수학 요소를 괄호 또는 다른 문자와 같은 지정된 문자로 프레임화합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 함수를 취합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_subscript/#imathelement) | 아래첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_subscript/#str) | 아래첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_superscript/#imathelement) | 위첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_superscript/#str) | 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_upper_limit/#imathelement) | 상한을 취합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_upper_limit/#str) | 상한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_lower_limit/#imathelement) | 하한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/set_lower_limit/#str) | 하한을 취합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes) | 제한 없이 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str) | 적분을 취합니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/group/#) | 아래 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/group/#char-mathtopbotpositions-mathtopbotpositions) | 아래 중괄호 또는 다른 그룹 문자와 같이 그룹 문자로 이 요소를 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/to_border_box/#) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/to_math_array/#) | 수직 배열에 넣습니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/accent/#char) | 악센트 표시(이 요소 위에 문자)를 설정합니다 |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/overbar/#) | 이 요소 위에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/underbar/#) | 이 요소 아래에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/to_box/#) | 이 요소를 비시각적 상자(논리적 그룹) <br/>            안에 배치합니다. 이는 방정식 또는 다른 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스 객체는 (예를 들어) 정렬점이 있거나 없거나 연산자 에뮬레이터로 사용할 수 있으며,<br/>            줄 바꿈 지점으로 사용하거나 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathradical/get_children/#) | 자식 요소를 가져옵니다 |


### 참조
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 클래스 [`MathRadical`](/slides/python-net/ko/aspose.slides.mathtext/mathradical)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)