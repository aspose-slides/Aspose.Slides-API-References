---
title: MathBlock class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathblock/
---
## MathBlock 클래스

MathParagraph에 포함된 수학 텍스트 인스턴스를 지정하며 자체 줄에서 시작합니다.
모든 수학 영역(방정식, 표현식, 방정식 또는 표현식 배열, 수식 등)은 math block으로 표시됩니다.

**Inheritance:**[`MathBlock`](/slides/python-net/ko/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)

MathBlock 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/__init__/#) | MathBlock 클래스를 새 인스턴스로 초기화합니다. |
| [`__init__(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/__init__/#imathelement) | 새 수학 블록을 만들고 지정된 요소를 그 안에 삽입합니다. |
| [`__init__(self, math_elements)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`count`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/count/) | 컬렉션에 실제로 포함된 자식 수학 요소의 수를 가져옵니다.<br/>            읽기 전용 **int**. |
| [`is_read_only`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/is_read_only/) | 자식 요소 컬렉션을 수정할 수 있기 때문에 false를 반환합니다. |

지정된 인덱스에 있는 IMathElement를 가져오거나 설정합니다.

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/__getitem__/) | 항목의 0부터 시작하는 인덱스 |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/join/#imathelement) | 수학 요소를 이 수학 블록과 결합합니다. |
| [`join(self, math_text)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/join/#str) | 수학 텍스트를 이 수학 블록과 결합합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/divide/#imathelement) | 이 분자와 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/divide/#str) | 이 분자와 지정된 분모로 분수를 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | 지정된 유형의 분수를 이 분자와 지정된 분모로 생성합니다. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/enclose/#char-char) | 이 블록의 자식 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레임을 만듭니다. |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | 이 블록의 자식 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레임을 만들고<br/>            구분 문자로 구분합니다. |
| [`enclose(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/enclose/#) | 수학 요소를 괄호로 둘러싸습니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/function/#imathelement) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 가져옵니다. |
| [`function(self, function_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/function/#str) | 이 인스턴스를 함수 이름으로 사용하여 인수의 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | 이 인스턴스를 인수로 사용하여 지정된 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 가져옵니다. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | 이 인스턴스를 인수로 사용하고 지정된 추가 인수를 사용하여 지정된 함수를 가져옵니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | 아래 첨자를 생성합니다. |
| [`set_subscript(self, subscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_subscript/#str) | 아래 첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | 위 첨자를 생성합니다. |
| [`set_superscript(self, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_superscript/#str) | 위 첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | 오른쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | 왼쪽에 아래 첨자와 위 첨자를 생성합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/radical/#imathelement) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`radical(self, degree)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/radical/#str) | 지정된 인수에서 주어진 차수의 수학적 루트를 지정합니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | 상한을 가져옵니다. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | 상한을 가져옵니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | 하한을 가져옵니다. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | 하한을 가져옵니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary 연산자를 생성합니다. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | N-ary 연산자를 생성합니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | 적분을 가져옵니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | 적분을 가져옵니다. |
| [`integral(self, integral_type)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | 한계 없이 적분을 가져옵니다. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | 적분을 가져옵니다. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | 적분을 가져옵니다. |
| [`group(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/group/#) | 하단 중괄호를 사용하여 이 요소를 그룹에 배치합니다. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | 하단 중괄호와 같은 그룹화 문자를 사용하여 이 요소를 그룹에 배치합니다. |
| [`to_border_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/to_border_box/#) | 이 요소를 경계 상자에 배치합니다. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | 이 요소를 경계 상자에 배치합니다. |
| [`to_math_array(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/to_math_array/#) | 자식 요소를 수직 배열에 배치합니다. |
| [`accent(self, accent_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/accent/#char) | 강세 기호(이 요소 위에 있는 문자)를 설정합니다. |
| [`overbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/overbar/#) | 이 요소 위에 바를 설정합니다. |
| [`underbar(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/underbar/#) | 이 요소 아래에 바를 설정합니다. |
| [`to_box(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/to_box/#) | 이 요소를 비시각적 상자(논리적 그룹화)에 배치합니다 <br/>            이는 방정식이나 다른 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다.<br/>            예를 들어, 박스 객체는 정렬점이 있거나 없는 연산자 에뮬레이터 역할을 할 수 있으며,<br/>            줄 바꿈 지점으로 사용되거나 내부에서 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다. |
| [`get_children(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/get_children/#) | 자식 요소를 가져옵니다. |
| [`add(self, item)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/add/#imathelement) | 수학 요소를 컬렉션 끝에 추가합니다. |
| [`clear(self)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/clear/#) | 컬렉션에서 모든 요소를 제거합니다. |
| [`contains(self, item)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/contains/#imathelement) | 컬렉션에 특정 값이 포함되어 있는지 확인합니다. |
| [`copy_to(self, array, array_index)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | 지정된 배열에 복사합니다. |
| [`remove(self, item)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/remove/#imathelement) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [`index_of(self, item)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/index_of/#imathelement) | 컬렉션에서 특정 수학 요소의 인덱스를 확인합니다. |
| [`insert(self, index, item)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | 지정된 인덱스에 MathElement를 컬렉션에 삽입합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/remove_at/#int) | 컬렉션의 지정된 인덱스에 있는 요소를 제거합니다. |
| [`join_block(self, other)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/join_block/#imathblock) | 다른 수학 블록을 이 블록과 결합합니다. |
| [`delimit(self, separator_character)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/delimit/#char) | 괄호 없이 구분 문자로 자식 요소를 구분합니다. |
| [`write_as_math_ml(self, stream)`](/slides/python-net/ko/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | 이 [`MathBlock`](/slides/python-net/ko/aspose.slides.mathtext/mathblock)의 내용을 MathML로 저장합니다. |

### 참고
* 클래스 [`MathBlock`](/slides/python-net/ko/aspose.slides.mathtext/mathblock)
* 클래스 [`MathElementBase`](/slides/python-net/ko/aspose.slides.mathtext/mathelementbase)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)