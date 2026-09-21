---
title: IMasterLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/imasterlayoutslidecollection/
---
## IMasterLayoutSlideCollection 클래스

정의된 마스터 슬라이드의 모든 레이아웃 슬라이드 컬렉션을 나타냅니다.
ILayoutSlideCollection 인터페이스를 확장하며, 개별 마스터 레이아웃 슬라이드 컬렉션 컨텍스트에서 레이아웃 슬라이드를 추가/삽입/제거/복제하는 메서드를 제공합니다.

IMasterLayoutSlideCollection 유형은 다음 멤버를 노출합니다:

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/add_clone/#ilayoutslide) | 지정된 레이아웃 슬라이드의 복사본을 컬렉션 끝에 추가합니다. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/insert_clone/#int-ilayoutslide) | 지정된 레이아웃 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/add/#slidelayouttype-str) | 새로운 레이아웃 슬라이드를 컬렉션 끝에 추가합니다. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/insert/#int-slidelayouttype-str) | 새로운 레이아웃 슬라이드를 컬렉션의 지정된 위치에 삽입합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/remove_at/#int) | 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/reorder/#int-ilayoutslide) | 컬렉션의 레이아웃 슬라이드를 지정된 위치로 이동합니다. |
| [`get_by_type(self, type)`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/get_by_type/#slidelayouttype) |  |
| [`remove(self, value)`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/remove/#ilayoutslide) |  |
| [`remove_unused(self)`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection/remove_unused/#) |  |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)