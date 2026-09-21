---
title: MathSuperscriptElement class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement 클래스

기본 요소와 오른쪽 위에 배치된 축소된 크기의 위첨자 요소로 구성된 위첨자 객체를 지정합니다.

**상속:**[`MathSuperscriptElement`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement) → [`BaseScript`](/slides/python-net/ko/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathSuperscriptElement 형식은 다음 멤버를 제공합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, base_arg, super_script)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/__init__/#imathelement-imathelement) | MathSuperscriptElement 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/base/) | 기본 인수 |
| [`superscript`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/superscript/) | 위첨자 |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/join/#imathelement) | 수학 요소를 결합하고 수학 블록을 생성합니다. |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/join/#str) | 수학 텍스트를 결합하고 수학 블록을 생성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement) | 이 분자를 사용하고 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/divide/#str) | 이 분자를 사용하고 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/enclose/#) | 수학 요소를 괄호 안에 넣습니다. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/enclose/#char-char) | 괄호와 같은 지정된 문자 또는 다른 문자를 프레임으로 사용하여 수학 요소를 감싸습니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#imathelement) | 첨자를 생성합니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#str) | 첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#imathelement) | 위첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#str) | 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 첨자와 위첨자를 생성합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#imathelement) | 상한값을 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#str) | 상한값을 지정합니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#imathelement) | 하한값을 지정합니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#str) | 하한값을 지정합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-항 연산자를 생성합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | N-항 연산자를 생성합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 수행합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 수행합니다. |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes) | 한계 없는 적분을 수행합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 수행합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str) | 적분을 수행합니다. |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/group/#) | 아래 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | 아래 중괄호 등과 같은 그룹 문자로 이 요소를 그룹에 배치합니다. |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#) | 이 요소를 테두리 박스에 배치합니다. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 박스에 배치합니다. |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/to_math_array/#) | 수직 배열에 넣습니다. |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/accent/#char) | 악센트 기호를 설정합니다(이 요소 위의 문자). |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/overbar/#) | 이 요소 위에 막대를 설정합니다. |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/underbar/#) | 이 요소 아래에 막대를 설정합니다. |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/to_box/#) | 이 요소를 비시각적 박스(논리적 그룹) <br/>            에 배치합니다. 이는 방정식의 구성 요소나 다른 수학 텍스트 인스턴스를 그룹화하는 데 사용됩니다.<br/>            박스화된 객체는 (예를 들어) 정렬점이 있거나 없거나에 따라 연산자 에뮬레이터 역할을 하거나, <br/>            줄 바꿈 지점으로 사용되거나, 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement/get_children/#) | 자식 요소를 가져옵니다. |

### 참고
* 클래스 [`BaseScript`](/slides/python-net/ko/aspose.slides.mathtext/basescript)
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 클래스 [`MathSuperscriptElement`](/slides/python-net/ko/aspose.slides.mathtext/mathsuperscriptelement)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)