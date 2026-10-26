---
title: MathNaryOperator class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator 클래스

Summation 및 Integral과 같은 N-ary 수학 객체를 지정합니다.
            운영자, 기본(또는 피연산자), 그리고 선택적인 상한 및 하한 한계로 구성됩니다. 
            N-ary 연산자의 예로는 합계, 합집합, 교집합, 적분이 있습니다.

**상속:**[`MathNaryOperator`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathNaryOperator 유형은 다음 멤버를 노출합니다:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | MathNaryOperator 클래스의 새 인스턴스를 초기화합니다. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | MathNaryOperator 클래스의 새 인스턴스를 초기화합니다. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | MathNaryOperator 클래스의 새 인스턴스를 초기화합니다. |

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/base/) | 기본 인수 |
| [`subscript`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/subscript/) | 예를 들어 적분의 경우 하한을 설정하는 아래첨자 인수를 지정합니다 |
| [`superscript`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/superscript/) | 예를 들어 적분의 경우 상한을 설정하는 위첨자 인수를 지정합니다 |
| [`operator`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/operator/) | Nary 연산자 문자<br/>            예: '∑', '∫' |
| [`limit_location`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/limit_location/) | 한계(아래첨자와 위첨자)의 위치 |
| [`grow_to_match_operand_height`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | 연산자 문자가 피연산자 높이에 맞게 수직으로 확장됩니다 |
| [`hide_subscript`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | 아래첨자 숨기기 |
| [`hide_superscript`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | 위첨자 숨기기 |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 만듭니다. |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/join/#str) | 수학 텍스트를 결합하여 수학 블록을 만듭니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | 이 분자와 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/divide/#str) | 이 분자와 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다. |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/enclose/#) | 수학 요소를 괄호로 감쌉니다. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자 또는 기타 문자로 프레임화하여 감쌉니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 받아들입니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 받아들입니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 받아들입니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 받아들입니다. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 받아들입니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 함수를 받아들입니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 함수를 받아들입니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | 아래첨자를 생성합니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | 아래첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | 위첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 생성합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | 상한을 받아들입니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | 상한을 받아들입니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | 하한을 받아들입니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | 하한을 받아들입니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 생성합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 생성합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 받아들입니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 받아들입니다. |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | 한계 없이 적분을 받아들입니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 받아들입니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | 적분을 받아들입니다. |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/group/#) | 아래 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | 아래 중괄호 등 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다. |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | 이 요소를 테두리 상자에 배치합니다. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 상자에 배치합니다. |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | 수직 배열에 배치합니다. |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/accent/#char) | 이 요소 위에 악센트 표시(문자)를 설정합니다. |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/overbar/#) | 이 요소 위에 막대를 설정합니다. |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/underbar/#) | 이 요소 아래에 막대를 설정합니다. |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/to_box/#) | 이 요소를 비시각적 상자(논리적 그룹) 안에 배치합니다.<br/>            이는 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스 객체는 (예를 들어) 정렬 지점이 있거나 없을 때 연산자 에뮬레이터 역할을 하거나,<br/>            줄 바꿈 지점으로 작동하거나, 내부에서 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator/get_children/#) | 자식 요소를 가져옵니다. |

### 관련 항목
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 클래스 [`MathNaryOperator`](/slides/python-net/ko/aspose.slides.mathtext/mathnaryoperator)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)