---
title: FontFallBackRule class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/fontfallbackrule/
---
## FontFallBackRule 클래스

글꼴 폴백 규칙을 나타냅니다.

FontFallBackRule 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/__init__/#int-int-str) | 새 인스턴스를 생성합니다. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | 새 인스턴스를 생성합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`range_start_index`](/slides/python-net/ko/aspose.slides/fontfallbackrule/range_start_index/) | 연속 유니코드 범위의 첫 번째 인덱스를 가져옵니다. |
| [`range_end_index`](/slides/python-net/ko/aspose.slides/fontfallbackrule/range_end_index/) | 연속 유니코드 범위의 마지막 인덱스를 가져옵니다. |
| [`count`](/slides/python-net/ko/aspose.slides/fontfallbackrule/count/) | 범위에 실제로 정의된 글꼴 수를 가져옵니다.<br/>            읽기 전용 **int**. |

지정된 인덱스의 글꼴 이름을 가져옵니다.
            읽기 전용 [`IFontFallBackRule`](/slides/python-net/ko/aspose.slides/ifontfallbackrule).

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides/fontfallbackrule/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | 새 글꼴을 FallBack 글꼴 목록에 추가합니다. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | 새 글꼴을 FallBack 글꼴 목록에 추가합니다. |
| [`to_array(self)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/to_array/#) | 이 규칙에 대한 모든 FallBack 글꼴이 들어 있는 배열을 생성하고 반환합니다. |
| [`to_array(self, start_index, count)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/to_array/#int-int) | 목록에서 지정된 범위에 해당하는 모든 FallBack 글꼴이 들어 있는 배열을 생성하고 반환합니다. |
| [`clear(self)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/clear/#) | 목록에서 모든 글꼴을 제거합니다. |
| [`remove(self, font_name)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/remove/#str) | 목록에서 특정 FallBack 글꼴의 첫 번째 발생을 제거합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/remove_at/#int) | 목록에서 지정된 인덱스에 있는 FallBack 글꼴을 제거합니다. |
| [`index_of(self, font_name)`](/slides/python-net/ko/aspose.slides/fontfallbackrule/index_of/#str) | 컬렉션에서 지정된 규칙의 인덱스를 반환합니다. |

### 참고
* 클래스 [`IFontFallBackRule`](/slides/python-net/ko/aspose.slides/ifontfallbackrule)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)