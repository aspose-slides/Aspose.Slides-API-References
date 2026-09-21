---
title: MathPhantom class
second_title: Aspose.Slides Python용 .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathphantom/
---
## MathPhantom 클래스

프레임 없는 수학 객체 (<m:phant>)를 나타내며, 자식 요소의 레이아웃에 영향을 주지만 반드시 표시할 필요는 없습니다. 팬텀은 기본 표현식을 숨기면서도 너비, 높이, 깊이를 유지하여 수식을 정렬하거나 공간을 확보할 수 있습니다. 가시성 및 기하학적 동작은 Show, ZeroWid, ZeroAsc, ZeroDesc 및 Transp와 같은 속성을 통해 제어됩니다.

**상속:**[`MathPhantom`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathPhantom 형식은 다음 멤버를 노출합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | [`MathPhantom`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom) 클래스의 새 인스턴스를 초기화합니다 <br/>            지정된 기본 수학 요소를 사용합니다. |

## 속성

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/base/) | 기본 인수 |
| [`show`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/show/) | 기본 요소가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [`zero_width`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/zero_width/) | 기본 요소의 너비를 0으로 처리할지 여부를 나타내는 값을 가져오거나 설정합니다. <br/>            |
| [`zero_asc`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/zero_asc/) | 기본 요소의 상승(기준선 위 높이)을 0으로 처리할지 여부를 나타내는 값을 가져오거나 설정합니다. <br/>            |
| [`zero_desc`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/zero_desc/) | 기본 요소의 하강(기준선 아래 깊이)을 0으로 처리할지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            |
| [`transp`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/transp/) | 클래스 기반 간격 규칙에 대해 팬텀이 투명한지 여부를 나타내는 값을 가져오거나 설정합니다. <br/>            |

## 메서드

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 만듭니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/join/#str) | 수학 텍스트를 결합하여 수학 블록을 만듭니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/divide/#imathelement) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/divide/#str) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/enclose/#) | 수학 요소를 괄호로 감쌉니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/enclose/#char-char) | 수학 요소를 괄호 등 지정된 문자로 프레임을 지정하여 감쌉니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로, 지정된 추가 인수를 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로, 지정된 추가 인수를 사용하여 지정된 함수를 취합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | 아래첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_subscript/#str) | 아래첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | 위첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_superscript/#str) | 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 근을 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 근을 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | 상한을 취합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | 상한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | 하한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | 하한을 취합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | 범위 없이 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | 적분을 취합니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/group/#) | 아래 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | 아래 중괄호 등 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/to_border_box/#) | 이 요소를 경계 박스에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 경계 박스에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/to_math_array/#) | 수직 배열에 배치합니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/accent/#char) | 이 요소 상단에 억음 부호(문자)를 설정합니다 |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/overbar/#) | 이 요소 상단에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/underbar/#) | 이 요소 하단에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/to_box/#) | 이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다 <br/>            이는 방정식이나 기타 수학 텍스트 구성 요소를 그룹화하는 데 사용됩니다.<br/>            박스 객체는 (예를 들어) 정렬점을 포함하거나 포함하지 않는 연산자 에뮬레이터 역할을 할 수 있으며, <br/>            줄 바꿈 지점으로 사용되거나 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom/get_children/#) | 자식 요소를 가져옵니다 |


### 참고
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 클래스 [`MathPhantom`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)