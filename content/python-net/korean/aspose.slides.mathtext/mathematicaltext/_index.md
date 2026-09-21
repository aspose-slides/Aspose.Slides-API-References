---
title: MathematicalText class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText 클래스

수학 텍스트

**상속:**[`MathematicalText`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathematicalText 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/__init__/#) | 기본 생성자 (String.Empty 값을 생성) |
| [`__init__(self, math_symbol)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/__init__/#char) | 단일 기호로 MathText 생성 |
| [`__init__(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/__init__/#str) | 텍스트에서 MathematicalText 생성 |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | 텍스트 및 형식 설정에서 MathematicalText 생성 |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`value`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/value/) | 텍스트 값 |
| [`format`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/format/) | 텍스트 서식 속성 |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/join/#str) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/divide/#str) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/enclose/#) | 수학 요소를 괄호 안에 넣습니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러씁니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | 지정된 함수를 이 인스턴스를 인수로 사용합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | 지정된 함수를 이 인스턴스를 인수로 사용합니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | 지정된 함수를 이 인스턴스를 인수로 사용합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 지정된 함수를 이 인스턴스를 인수로 사용하고 추가 인수를 지정합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 지정된 함수를 이 인스턴스를 인수로 사용하고 추가 인수를 지정합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | 아래 첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | 아래 첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | 위 첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | 위 첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | 상한을 취합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | 상한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | 하한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | 하한을 취합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | 제한 없이 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | 적분을 취합니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/group/#) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호와 같은 그룹 문자 또는 다른 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 상자에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | 수직 배열에 넣습니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/accent/#char) | 강세 부호를 설정합니다 (이 요소 위의 문자) |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/overbar/#) | 이 요소 위에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/underbar/#) | 이 요소 아래에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/to_box/#) | 이 요소를 비시각적 박스(논리적 그룹화) 안에 배치합니다 <br/>            이는 방정식 구성 요소나 다른 수학 텍스트 인스턴스를 그룹화하는 데 사용됩니다.<br/>            박스 객체는 (예를 들어) 정렬 지점이 있거나 없거나 연산자 에뮬레이터 역할을 할 수 있으며, <br/>            줄 바꿈 지점으로 사용되거나 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### 참고
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 클래스 [`MathematicalText`](/slides/python-net/ko/aspose.slides.mathtext/mathematicaltext)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)