---
title: IFontFallBackRule class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ifontfallbackrule/
---
## IFontFallBackRule 클래스

폰트 대체 규칙을 나타냅니다.

IFontFallBackRule 형식은 다음 멤버를 제공합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`range_start_index`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/range_start_index/) | 연속 유니코드 범위의 첫 번째 인덱스를 가져옵니다. |
| [`range_end_index`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/range_end_index/) | 연속 유니코드 범위의 마지막 인덱스를 가져옵니다. |
| [`count`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/count/) | 범위에 실제로 정의된 폰트 수를 가져옵니다. |

지정된 인덱스에 있는 폰트 이름을 가져옵니다.

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#str) | 새 폰트(들)를 대체 폰트 목록에 추가합니다. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#liststr) | 새 폰트를 대체 폰트 목록에 추가합니다. |
| [`to_array(self)`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/to_array/#) | 이 규칙에 대한 모든 대체 폰트를 배열로 생성하여 반환합니다. |
| [`to_array(self, start_index, count)`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/to_array/#int-int) | 목록에서 지정된 범위의 모든 대체 폰트를 배열로 생성하여 반환합니다. |
| [`clear(self)`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/clear/#) | 목록에서 모든 폰트를 제거합니다. |
| [`remove(self, font_name)`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/remove/#str) | 목록에서 특정 대체 폰트의 첫 번째 항목을 제거합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/remove_at/#int) | 목록의 지정된 인덱스에 있는 대체 폰트를 제거합니다. |
| [`index_of(self, font_name)`](/slides/python-net/ko/aspose.slides/ifontfallbackrule/index_of/#str) | 컬렉션에서 지정된 규칙의 인덱스를 반환합니다. |


### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)