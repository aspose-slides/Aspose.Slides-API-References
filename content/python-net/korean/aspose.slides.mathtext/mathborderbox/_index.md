---
title: MathBorderBox class
second_title: Aspose.Slides Python용 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox 클래스

IMathElement 주위에 직사각형 또는 다른 형태의 테두리를 그립니다.

**상속:**[`MathBorderBox`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathBorderBox 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | 직사각형 테두리를 가진 MathBorderBox 요소를 생성합니다 |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | MathBorderBox 요소를 생성합니다 |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/base/) | 기본 인수 |
| [`hide_top`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/hide_top/) | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [`hide_bottom`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [`hide_left`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/hide_left/) | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [`hide_right`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/hide_right/) | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [`strikethrough_horizontal`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [`strikethrough_vertical`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Strikethrough Bottom-Left to Top-Right (default is false).<br/>            좌하단에서 우상단으로 취소선(기본값은 false).<br/>            테두리 상자의 좌하단 모서리에서 우상단 모서리까지 대각선 취소선의 숨김 또는 표시 상태를 지정합니다. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Strikethrough Top-Left to Bottom-Right (default is false).<br/>            좌상단에서 우하단으로 취소선(기본값은 false).<br/>            테두리 상자의 좌상단 모서리에서 우하단 모서리까지 대각선 취소선의 숨김 또는 표시 상태를 지정합니다. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/join/#str) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/divide/#str) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | 이 분자와 지정된 분모를 사용하여 지정된 유형의 분수를 생성합니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/enclose/#) | 수학 요소를 괄호로 감쌉니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레임을 두어 감쌉니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 추가 인수를 지정하여 지정된 함수를 취합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | 아래첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | 아래첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | 위첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | 상한을 취합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | 상한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | 하한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | 하한을 취합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | 제한 없이 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | 적분을 취합니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/group/#) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/to_border_box/#) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/to_math_array/#) | 수직 배열에 넣습니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/accent/#char) | 악센트 표시를 설정합니다(이 요소 위에 문자를 놓음) |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/overbar/#) | 이 요소의 상단에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/underbar/#) | 이 요소의 하단에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/to_box/#) | 이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다 <br/>            이는 방정식이나 기타 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스형 객체는 (예를 들어) 정렬 지점이 있거나 없는 연산자 에뮬레이터 역할을 하거나,<br/>            줄 바꿈 지점으로 사용되거나, 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다 |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox/get_children/#) | 자식 요소를 가져옵니다 |

### 참고
* 클래스 [`MathBorderBox`](/slides/python-net/ko/aspose.slides.mathtext/mathborderbox)
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)