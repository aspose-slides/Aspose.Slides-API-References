---
title: MathRightSubSuperscriptElement class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement 클래스

Base와 그 오른쪽에 배치된 아래첨자와 위첨자로 구성되는 Sub-Superscript 객체를 지정합니다.

**Inheritance:**[`MathRightSubSuperscriptElement`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement) → [`BaseScript`](/slides/python-net/ko/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathRightSubSuperscriptElement 유형은 다음 멤버를 제공합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, base_arg, sub_script, super_script)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/__init__/#imathelement-imathelement-imathelement) | MathRightSubSuperscriptElement 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/base/) | 기본 인수 |
| [`subscript`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/) | 아래첨자 인수 |
| [`superscript`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript/) | 위첨자 인수 |
| [`align_scripts`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/align_scripts/) | 아래첨자/위첨자의 정렬을 지정합니다. <br/> true인 경우 아래첨자와 위첨자가 서로 수평으로 정렬됩니다.<br/> false인 경우 기본의 모양에 맞게 커닝됩니다.<br/> 기본값은 false입니다. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#imathelement) | 수학 요소를 결합하고 수학 블록을 형성합니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#str) | 수학 텍스트를 결합하고 수학 블록을 형성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str) | 이 분자와 지정된 분모로 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#) | 수학 요소를 괄호로 감쌉니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#char-char) | 괄호와 같은 지정된 문자 또는 다른 문자로 수학 요소를 프레임처럼 감쌉니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 포함하여 지정된 함수를 취합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#imathelement) | 아래첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#str) | 아래첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#imathelement) | 위첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#str) | 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래첨자와 위첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#imathelement) | 상한을 취합니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#str) | 상한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#imathelement) | 하한을 취합니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#str) | 하한을 취합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-항 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | N-항 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 취합니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes) | 한계 없이 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 취합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str) | 적분을 취합니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호 또는 다른 구분 문자를 사용하여 이 요소를 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#) | 이 요소를 경계 상자에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 경계 상자에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_math_array/#) | 수직 배열에 배치합니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/accent/#char) | 강세 표시(이 요소 상단의 문자)를 설정합니다 |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/overbar/#) | 이 요소 상단에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/underbar/#) | 이 요소 하단에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_box/#) | 이 요소를 비시각적 상자(논리적 그룹화) 안에 배치합니다. <br/> 이는 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다.<br/> 상자 안의 객체는 (예를 들어) 정렬점이 있든 없든 연산자 에뮬레이터 역할을 하거나,<br/> 줄 바꿈 지점으로 사용하거나, 내부에서 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다 |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_children/#) | 자식 요소를 가져옵니다 |


### 참조
* 클래스 [`BaseScript`](/slides/python-net/ko/aspose.slides.mathtext/basescript)
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 클래스 [`MathRightSubSuperscriptElement`](/slides/python-net/ko/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)