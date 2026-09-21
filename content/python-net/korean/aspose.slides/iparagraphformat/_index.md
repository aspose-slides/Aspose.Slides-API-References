---
title: IParagraphFormat class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iparagraphformat/
---
## IParagraphFormat 클래스

이 클래스는 단락 서식 속성을 포함합니다. [`IParagraphFormatEffectiveData`](/slides/python-net/ko/aspose.slides/iparagraphformateffectivedata)와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.

IParagraphFormat 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`bullet`](/slides/python-net/ko/aspose.slides/iparagraphformat/bullet/) | 단락의 글머리표 형식을 반환합니다.<br/>읽기 전용 [`IBulletFormat`](/slides/python-net/ko/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/ko/aspose.slides/iparagraphformat/depth/) | 단락의 깊이를 반환하거나 설정합니다.<br/>값 0은 정의되지 않은 값을 의미합니다.<br/>읽기/쓰기 **int**. |
| [`alignment`](/slides/python-net/ko/aspose.slides/iparagraphformat/alignment/) | 상속이 없는 단락에서 텍스트 정렬을 반환하거나 설정합니다.<br/>읽기/쓰기 [`TextAlignment`](/slides/python-net/ko/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/ko/aspose.slides/iparagraphformat/space_within/) | 단락에서 기준선 사이의 간격을 반환하거나 설정합니다. 양수 값은 백분율을 의미하고, 음수는 포인트 단위 크기를 의미합니다. 상속이 적용되지 않습니다.<br/>읽기/쓰기 **float**. |
| [`space_before`](/slides/python-net/ko/aspose.slides/iparagraphformat/space_before/) | 상속이 없는 단락에서 첫 번째 줄 앞의 공백 양을 반환하거나 설정합니다.<br/>양수 값은 공백이 차지해야 할 글꼴 크기의 백분율을 지정합니다.<br/>음수 값은 공백의 크기를 포인트 단위로 지정합니다.<br/>읽기/쓰기 **float**. |
| [`space_after`](/slides/python-net/ko/aspose.slides/iparagraphformat/space_after/) | 상속이 없는 단락에서 마지막 줄 뒤의 공백 양을 반환하거나 설정합니다.<br/>양수 값은 공백이 차지해야 할 글꼴 크기의 백분율을 지정합니다.<br/>음수 값은 공백의 크기를 포인트 단위로 지정합니다.<br/>읽기/쓰기 **float**. |
| [`east_asian_line_break`](/slides/python-net/ko/aspose.slides/iparagraphformat/east_asian_line_break/) | 단락에서 동아시아 줄 바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다.<br/>읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/ko/aspose.slides/iparagraphformat/right_to_left/) | 단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다.<br/>읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/ko/aspose.slides/iparagraphformat/latin_line_break/) | 단락에서 라틴 줄 바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다.<br/>읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/ko/aspose.slides/iparagraphformat/hanging_punctuation/) | 단락에서 걸려 있는 구두점이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다.<br/>읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/ko/aspose.slides/iparagraphformat/margin_left/) | 상속이 없는 단락에서 왼쪽 여백을 반환하거나 설정합니다.<br/>읽기/쓰기 **float**. |
| [`margin_right`](/slides/python-net/ko/aspose.slides/iparagraphformat/margin_right/) | 상속이 없는 단락에서 오른쪽 여백을 반환하거나 설정합니다.<br/>읽기/쓰기 **float**. |
| [`indent`](/slides/python-net/ko/aspose.slides/iparagraphformat/indent/) | 상속이 없는 단락에서 첫 번째 줄 들여쓰기/걸려 있는 들여쓰기를 반환하거나 설정합니다. 걸려 있는 들여쓰기는 음수 값으로 정의할 수 있습니다.<br/>읽기/쓰기 **float**. |
| [`default_tab_size`](/slides/python-net/ko/aspose.slides/iparagraphformat/default_tab_size/) | 상속이 없는 단락에서 기본 탭 크기를 반환하거나 설정합니다.<br/>읽기/쓰기 **float**. |
| [`tabs`](/slides/python-net/ko/aspose.slides/iparagraphformat/tabs/) | 단락의 탭을 반환합니다. 상속이 적용되지 않습니다.<br/>읽기 전용 [`ITabCollection`](/slides/python-net/ko/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/ko/aspose.slides/iparagraphformat/font_alignment/) | 상속이 없는 단락에서 글꼴 정렬을 반환하거나 설정합니다.<br/>읽기/쓰기 [`FontAlignment`](/slides/python-net/ko/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/ko/aspose.slides/iparagraphformat/default_portion_format/) | 단락의 기본 부분 서식을 반환합니다. 상속이 적용되지 않습니다.<br/>읽기 전용 [`IPortionFormat`](/slides/python-net/ko/aspose.slides/iportionformat). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ko/aspose.slides/iparagraphformat/get_effective/#) | 상속이 적용된 효과적인 단락 서식 데이터를 가져옵니다. |

### 비고

이 클래스는 특정 단락에 정의된 단락 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으므로 대부분의 경우 값이 "undefined"(정의되지 않음)이라는 의미가 됩니다.

상속을 포함한 효과적인 서식 매개변수 값을 얻으려면 [`IParagraphFormat.get_effective`](/slides/python-net/ko/aspose.slides/iparagraphformat/get_effective) 메서드를 사용해야 하며, 이 메서드는 [`IParagraphFormatEffectiveData`](/slides/python-net/ko/aspose.slides/iparagraphformateffectivedata) 인스턴스를 반환합니다.

### 참조
* 클래스 [`IParagraphFormatEffectiveData`](/slides/python-net/ko/aspose.slides/iparagraphformateffectivedata)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)