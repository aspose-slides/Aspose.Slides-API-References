---
title: ISectionCollection class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/isectioncollection/
---
## ISectionCollection 클래스

섹션의 컬렉션을 나타냅니다.

ISectionCollection 유형은 다음 멤버를 노출합니다:

지정된 인덱스에 있는 요소를 가져옵니다.
읽기 전용 [`ISection`](/slides/python-net/ko/aspose.slides/isection).

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides/isectioncollection/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_section(self, name, started_from_slide)`](/slides/python-net/ko/aspose.slides/isectioncollection/add_section/#str-islide) | 특정 슬라이드에서 시작되는 새 섹션을 추가합니다. |
| [`add_empty_section(self, name, index)`](/slides/python-net/ko/aspose.slides/isectioncollection/add_empty_section/#str-int) | 컬렉션의 지정된 위치에 빈 섹션을 추가합니다. |
| [`remove_section_with_slides(self, section)`](/slides/python-net/ko/aspose.slides/isectioncollection/remove_section_with_slides/#isection) | 섹션 및 섹션에 포함된 슬라이드를 제거합니다. |
| [`remove_section(self, section)`](/slides/python-net/ko/aspose.slides/isectioncollection/remove_section/#isection) | 섹션을 제거합니다. 섹션에 포함된 슬라이드는 이전 섹션에 병합됩니다. |
| [`reorder_section_with_slides(self, section, index)`](/slides/python-net/ko/aspose.slides/isectioncollection/reorder_section_with_slides/#isection-int) | 섹션 및 해당 슬라이드를 컬렉션에서 지정된 위치로 이동합니다. |
| [`append_empty_section(self, name)`](/slides/python-net/ko/aspose.slides/isectioncollection/append_empty_section/#str) | 컬렉션 끝에 빈 섹션을 추가합니다. |
| [`index_of(self, section)`](/slides/python-net/ko/aspose.slides/isectioncollection/index_of/#isection) | 컬렉션에서 지정된 섹션의 인덱스를 반환합니다. |
| [`clear(self)`](/slides/python-net/ko/aspose.slides/isectioncollection/clear/#) | 컬렉션에서 모든 섹션을 제거합니다. |

### 참고
* 클래스 [`ISection`](/slides/python-net/ko/aspose.slides/isection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)