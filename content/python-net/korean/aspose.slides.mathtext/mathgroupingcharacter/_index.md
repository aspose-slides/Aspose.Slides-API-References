---
title: MathGroupingCharacter class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter 클래스

식 위나 아래에 그룹화 기호를 지정하며, 일반적으로 요소 간의 관계를 강조하기 위해 사용됩니다

**Inheritance:**[`MathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathGroupingCharacter 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | MathGroupingCharacter 클래스의 새 인스턴스를 초기화합니다 <br/> 기본 그룹화 문자 U+23DF (BOTTOM CURLY BRACKET) 사용 |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | MathGroupingCharacter 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`base`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/base/) | 기본 인수 |
| [`character`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/character/) | 그룹화 문자<br/>            기본 값: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/position/) | 그룹화 문자의 위치.<br/>            기본값: Bottom |
| [`vertical_justification`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | 그룹 문자의 수직 정렬.<br/>            객체의 기준선에 대한 정렬을 지정합니다.<br/>            예를 들어, 그룹 문자가 객체 위에 있을 때,<br/>            VerticalJustification이 Top이면 객체의 상단이 기준선에 맞춰짐을 의미합니다;<br/>            VerticalJustification이 Bottom으로 설정되면 객체의 하단이 기준선에 맞춰짐을 의미합니다<br/>            기본값: Position=Top인 경우 Bottom, Position=Bottom인 경우 Top |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | 수학 요소를 결합하여 수학 블록을 형성합니다 |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | 수학 텍스트를 결합하여 수학 블록을 형성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | 이 분자와 지정된 분모를 사용하여 분수를 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다 |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | 수학 요소를 괄호로 둘러씁니다 |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | 수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레임을 만듭니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 정의합니다 |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 정의합니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다 |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다 |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 추가 지정 인수를 포함하여 지정된 함수를 가져옵니다 |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 추가 지정 인수를 포함하여 지정된 함수를 가져옵니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | 아랫첨자를 생성합니다 |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | 아랫첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | 윗첨자를 생성합니다 |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | 윗첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아랫첨자와 윗첨자를 생성합니다 |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아랫첨자와 윗첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아랫첨자와 윗첨자를 생성합니다 |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아랫첨자와 윗첨자를 생성합니다 |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | 상한을 가져옵니다 |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | 상한을 가져옵니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | 하한을 가져옵니다 |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | 하한을 가져옵니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N진 연산자를 생성합니다 |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | N진 연산자를 생성합니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 가져옵니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 가져옵니다 |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | 한계 없이 적분을 가져옵니다 |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 가져옵니다 |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | 적분을 가져옵니다 |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/group/#) | 이 요소를 아래 중괄호를 사용하여 그룹에 배치합니다 |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | 이 요소를 아래 중괄호 등과 같은 그룹화 문자를 사용하여 그룹에 배치합니다 |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | 이 요소를 테두리 박스에 배치합니다 |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 테두리 박스에 배치합니다 |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | 수직 배열에 배치합니다 |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | 악센트 표시(이 요소 위에 있는 문자)를 설정합니다 |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | 이 요소 위에 바를 설정합니다 |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | 이 요소 아래에 바를 설정합니다 |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | 이 요소를 시각적이지 않은 상자(논리적 그룹화)에 배치합니다 <br/>            이는 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            상자 객체는 (예를 들어) 정렬점이 있거나 없을 수 있는 연산자 에뮬레이터 역할을 하거나,<br/>            줄 바꿈 지점으로 작용하거나, 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | 자식 요소를 가져옵니다 |

### 참조
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 클래스 [`MathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/mathgroupingcharacter)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)