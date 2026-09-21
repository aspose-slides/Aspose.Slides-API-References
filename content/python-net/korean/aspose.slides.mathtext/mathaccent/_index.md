---
title: MathAccent class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathaccent/
---
## MathAccent 클래스

베이스와 결합 부호를 포함하는 악센트 함수를 지정합니다  
            예시: 𝑎́

**Inheritance:**[`MathAccent`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathAccent 형식은 다음 멤버를 노출합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | 기본 악센트 문자 값을 사용하여 지정된 수학 요소에 적용되는 수학 악센트를 생성합니다 |
| [`__init__(self, element, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | 지정된 수학 요소에 적용되는 수학 악센트를 생성합니다 |

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/base/) | 악센트가 적용된 인수 |
| [`character`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/character/) | Accent Character<br/>            값은 (U+0300–U+036F) 또는 (U+20D0–U+20EF) 범위 내에 있어야 합니다<br/>            Default value: Combining Circumflex Accent (U+0302) |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/join/#str) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/divide/#imathelement) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/divide/#str) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/enclose/#) | 수학 요소를 괄호로 둘러싸습니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/enclose/#char-char) | 괄호와 같은 지정된 문자나 다른 문자로 수학 요소를 둘러싸 프레임을 만듭니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수에 대한 함수를 취합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수에 대한 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | 아래첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_subscript/#str) | 아래첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | 위첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_superscript/#str) | 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | 상한값을 취합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | 상한값을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | 하한값을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | 하한값을 취합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-항 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | N-항 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | 한계 없이 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | 적분을 취합니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/group/#) | 아래 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | 아래 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/to_border_box/#) | 이 요소를 경계 상자에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 경계 상자에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/to_math_array/#) | 수직 배열에 넣습니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/accent/#char) | 악센트 표시(이 요소 위에 있는 문자)를 설정합니다 |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/overbar/#) | 이 요소의 위에 막대를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/underbar/#) | 이 요소의 아래에 막대를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/to_box/#) | 이 요소를 비시각적 박스(논리적 그룹화) <br/>            에 배치합니다. 이는 방정식 또는 다른 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스화된 객체는 (예를 들어) 정렬 지점이 있거나 없을 때 연산자 에뮬레이터 역할을 할 수 있으며,<br/>            줄 바꿈 지점으로 작동하거나 내부에 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent/get_children/#) | 자식 요소를 가져옵니다 |

### 참고
* class [`MathAccent`](/slides/python-net/ko/aspose.slides.mathtext/mathaccent)
* class [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)