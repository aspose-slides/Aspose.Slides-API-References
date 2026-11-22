---
title: MathDelimiter class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter 클래스

시작 및 종료 문자(예: 괄호, 중괄호, 대괄호 및 수직 막대)와 내부에 하나 이상의 수학 요소가 지정된 문자로 구분된 구분자 객체를 지정합니다. 예시: (𝑥2); [𝑥2|𝑦2]

**Inheritance:**[`MathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathDelimiter 유형은 다음 멤버를 제공합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | 지정된 요소를 단일 기본 인수로 사용하여 MathDelimiter를 초기화합니다 |

## 속성

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/arguments/) | 구분 문자로 구분된 하나 이상의 수학 요소 |
| [`beginning_character`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character는 시작, 즉 여는 구분 문자를 지정합니다.<br/>            수학 구분자는 괄호, 대괄호, 중괄호와 같은 둘러싸는 문자입니다.<br/>            기본값: '('. |
| [`separator_character`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character는 구분 객체에서 인수를 구분하는 문자를 지정합니다.<br/>            기본값: '\|'. |
| [`ending_character`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character는 종료, 즉 닫는 구분 문자를 지정합니다.<br/>            수학 구분자는 괄호, 대괄호, 중괄호와 같은 둘러싸는 문자입니다.<br/>            기본값: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | BeginningCharacter, SeparatorCharacter, EndingCharacter의 성장 여부를 지정합니다.<br/>            true인 경우 구분자는 피연산자 높이에 맞게 수직으로 커집니다.<br/>            기본값은 true 입니다. |
| [`delimiter_shape`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | 구분 객체에서 구분자의 형태를 지정합니다.<br/>            MathDelimiterShape.Centered인 경우, 구분자는 수학 텍스트의 수학 축을 중심으로 배치되고 내용 전체 높이에 맞게 조정됩니다.<br/>            MathDelimiterShape.Match인 경우, 높이와 형태가 내용에 정확히 맞도록 변경됩니다. |

## 메서드

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/join/#str) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/divide/#str) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/enclose/#) | 수학 요소를 괄호로 감쌉니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레임화하여 감쌉니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 가져옵니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 가져옵니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 가져옵니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 가져옵니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | 아래첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | 아래첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | 위첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 제곱근을 지정합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 제곱근을 지정합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | 상한을 가져옵니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | 상한을 가져옵니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | 하한을 가져옵니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | 하한을 가져옵니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-항 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | N-항 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 가져옵니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 가져옵니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | 범위 없이 적분을 가져옵니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 가져옵니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | 적분을 가져옵니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/group/#) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | 이 요소를 경계 상자에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 경계 상자에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | 수직 배열에 넣습니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/accent/#char) | 강세 표시(이 요소 위에 있는 문자)를 설정합니다 |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/overbar/#) | 이 요소 위에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/underbar/#) | 이 요소 아래에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/to_box/#) | 이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다 <br/>            이는 방정식이나 다른 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스화된 객체는 예를 들어 정렬 지점이 있든 없든 연산자 에뮬레이터 역할을 할 수 있으며, <br/>            줄 바꿈 지점으로 사용되거나 내부에 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. |
| [`delimit(self, separator_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/delimit/#char) | 지정된 구분 문자를 사용하여 인수를 구분합니다 |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter/get_children/#) | 자식 요소를 가져옵니다 |


### 참조
* 클래스 [`MathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter)
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)