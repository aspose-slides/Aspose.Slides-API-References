---
title: MathBox class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathbox/
---
## MathBox 클래스

수학 요소의 논리적 박싱(패키징)을 지정합니다.  
예를 들어, 박스화된 객체는 정렬 지점이 있든 없든 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점으로 사용되거나, 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다.  
예를 들어, "==" 연산자는 줄 바꿈을 방지하기 위해 박스화되어야 합니다.

**상속:**[`MathBox`](/slides/python-net/ko/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathBox 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/__init__/#imathelement) | 지정된 요소를 인수로 사용하여 MathBox를 초기화합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/base/) | 기본 인수 |
| [`operator_emulator`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/operator_emulator/) | 연산자 에뮬레이터.<br/>            true인 경우, 박스와 그 내용은 단일 연산자처럼 동작하며 연산자의 속성을 상속합니다. <br/>            예를 들어, 이 문자는 줄 바꿈 지점으로 사용될 수 있으며 다른 연산자와 정렬될 수 있음을 의미합니다.<br/>            연산자 에뮬레이터는 '=='와 같이 하나 이상의 글리프가 결합하여 연산자를 형성할 때 자주 사용됩니다.<br/>            기본값: false |
| [`no_break`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/no_break/) | 줄 바꿈 없음<br/>            이 속성은 객체 박스에 대한 "unbreakable" 속성을 지정합니다. true인 경우, 박스 내부에서 줄 바꿈이 발생하지 않습니다.<br/>            이는 둘 이상의 이진 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다.<br/>            이 요소가 지정되지 않으면, 박스 내부에서 줄 바꿈이 발생할 수 있습니다.<br/>            기본값: true |
| [`differential`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/differential/) | 미분<br/>            true인 경우, 박스는 미분(예: 적분식의 𝑑𝑥) 역할을 하며 수학적 미분에 적합한 가로 간격을 받습니다.<br/>            기본값: false |
| [`alignment_point`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/alignment_point/) | true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 방정식에서 지정된 정렬 지점과 이와 정렬될 수 있습니다.<br/>            기본값: false |
| [`explicit_break`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/explicit_break/) | 명시적 줄 바꿈은 Box 객체 시작에 줄 바꿈이 있는지를 지정합니다, <br/>            즉, 줄이 박스 객체 시작에서 래핑됩니다.<br/>            이전 수학 텍스트 줄에 있는 연산자의 번호를 지정하며, 이는 현재 수학 텍스트 줄의 정렬 지점으로 사용됩니다.<br/>            가능한 값: 1..255<br/>            기본값: 0 (명시적 줄 바꿈 없음) |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 형성합니다. |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/join/#str) | 수학 텍스트를 결합하여 수학 블록을 형성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/divide/#imathelement) | 주어진 분자와 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/divide/#str) | 주어진 분자와 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | 주어진 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | 주어진 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/enclose/#) | 수학 요소를 괄호로 둘러쌉니다. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레임합니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | 아래 첨자를 생성합니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_subscript/#str) | 아래 첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | 위 첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_superscript/#str) | 위 첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | 상한을 취합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | 상한을 취합니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | 하한을 취합니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | 하한을 취합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 생성합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 생성합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다. |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | 한계 없이 적분을 취합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | 적분을 취합니다. |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/group/#) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호 등과 같은 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다. |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/to_border_box/#) | 이 요소를 경계 상자에 배치합니다. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 경계 상자에 배치합니다. |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/to_math_array/#) | 수직 배열에 배치합니다. |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/accent/#char) | 액센트 표시(이 요소 위의 문자)를 설정합니다. |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/overbar/#) | 이 요소 위에 막대를 설정합니다. |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/underbar/#) | 이 요소 아래에 막대를 설정합니다. |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/to_box/#) | 이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다 <br/>            이는 방정식이나 다른 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스화된 객체는 (예를 들어) 정렬 지점이 있든 없든 연산자 에뮬레이터 역할을 하거나, <br/>            줄 바꿈 지점으로 사용되거나, 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathbox/get_children/#) | 자식 요소를 가져옵니다. |

### 참조
* 클래스 [`MathBox`](/slides/python-net/ko/aspose.slides.mathtext/mathbox)
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)