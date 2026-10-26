---
title: MathFraction class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathfraction/
---
## MathFraction 클래스

Specifies the fraction object, consisting of a numerator and denominator separated by a fraction bar.
            The fraction bar can be horizontal or diagonal, depending on the fraction properties.
            The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar.

**상속:**[`MathFraction`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

The MathFraction type exposes the following members:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | 지정된 분자, 분모 및 유형으로 MathFraction을 초기화합니다. |
| [`__init__(self, numerator, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | 'Bar' 유형의 MathFraction을 지정된 분자와 분모로 초기화합니다. |

## 속성

| Property | Description |
| :- | :- |
| [`fraction_type`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/fraction_type/) | Fraction type<br/>            Default: Bar |
| [`numerator`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/numerator/) | 분자 |
| [`denominator`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/denominator/) | 분모 |

## 메서드

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 형성합니다. |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/join/#str) | 수학 텍스트를 결합하여 수학 블록을 형성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/divide/#imathelement) | 이 분자와 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/divide/#str) | 이 분자와 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/enclose/#) | 수학 요소를 괄호로 둘러씁니다. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레임화하여 감쌉니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 가져옵니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 제공하여 지정된 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 제공하여 지정된 함수를 가져옵니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | 아래첨자를 생성합니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_subscript/#str) | 아래첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | 위첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_superscript/#str) | 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | 상한을 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | 상한을 지정합니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | 하한을 지정합니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | 하한을 지정합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-항 연산자를 생성합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | N-항 연산자를 생성합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 지정합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 지정합니다. |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | 한계 없이 적분을 지정합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 지정합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | 적분을 지정합니다. |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/group/#) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호 등과 같은 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다. |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/to_border_box/#) | 이 요소를 테두리 상자에 배치합니다. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 상자에 배치합니다. |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/to_math_array/#) | 수직 배열에 배치합니다. |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/accent/#char) | 강세 기호(이 요소 위에 표시되는 문자)를 설정합니다. |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/overbar/#) | 이 요소 상단에 막대를 설정합니다. |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/underbar/#) | 이 요소 하단에 막대를 설정합니다. |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/to_box/#) | 이 요소를 비시각적 상자(논리적 그룹화)에 배치합니다 <br/>            이는 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            상자 객체는 (예를 들어) 정렬점을 사용하거나 사용하지 않는 연산자 에뮬레이터 역할을 할 수 있으며, <br/>            줄바꿈 지점으로 사용되거나 내부에 줄바꿈이 허용되지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction/get_children/#) | 자식 요소를 가져옵니다. |

### 참고
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 클래스 [`MathFraction`](/slides/python-net/ko/aspose.slides.mathtext/mathfraction)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)