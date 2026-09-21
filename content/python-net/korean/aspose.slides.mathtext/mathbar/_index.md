---
title: MathBar class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathbar/
---
## MathBar 클래스

바 함수(기본 인수와 위바 혹은 아래바로 구성됨)를 지정합니다.

**상속:**[`MathBar`](/slides/python-net/ko/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathBar 유형은 다음 멤버를 노출합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/__init__/#imathelement) | 위바(Top 위치)와 함께 MathBar를 초기화합니다 |
| [`__init__(self, element, position)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | 지정된 위치와 함께 MathBar를 초기화합니다 |

## 속성

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/base/) | 기본 인수 |
| [`position`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/position/) | 바 라인의 위치. <br/>            기본값: Top |

## 메서드

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 생성합니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/join/#str) | 수학 텍스트를 결합하여 수학 블록을 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/divide/#imathelement) | 이 분자와 지정된 분모로 분수를 만듭니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/divide/#str) | 이 분자와 지정된 분모로 분수를 만듭니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 만듭니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 만듭니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/enclose/#) | 수학 요소를 괄호로 둘러싸습니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/enclose/#char-char) | 수학 요소를 괄호 등 지정된 문자나 다른 문자로 프레임을 만들어 둘러싸습니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | 아래 첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_subscript/#str) | 아래 첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | 위 첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_superscript/#str) | 위 첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | 상한을 취합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | 상한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | 하한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | 하한을 취합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | 제한 없이 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | 적분을 취합니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/group/#) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호 등 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/to_border_box/#) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/to_math_array/#) | 수직 배열에 배치합니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/accent/#char) | 강세 표시(이 요소 위에 있는 문자)를 설정합니다 |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/overbar/#) | 이 요소의 상단에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/underbar/#) | 이 요소의 하단에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/to_box/#) | 이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다 <br/>            이는 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스화된 객체는 (예를 들어) 정렬 지점이 있거나 없는 연산자 에뮬레이터 역할을 할 수 있으며, <br/>            줄 바꿈 지점으로 사용되거나 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbar/get_children/#) | 자식 요소를 가져옵니다 |

### 관련 항목
* 클래스 [`MathBar`](/slides/python-net/ko/aspose.slides.mathtext/mathbar)
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)