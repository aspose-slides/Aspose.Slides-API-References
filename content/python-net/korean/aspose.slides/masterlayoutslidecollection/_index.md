---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection 클래스

정의된 마스터 슬라이드의 모든 레이아웃 슬라이드 컬렉션을 나타냅니다.
            LayoutSlideCollection 클래스를 확장하여 마스터 레이아웃 슬라이드의 개별 컬렉션 컨텍스트에서 레이아웃 슬라이드를 추가/삽입/제거/복제/재정렬하는 메서드를 제공합니다.

**상속:**[`MasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/ko/aspose.slides/layoutslidecollection)

MasterLayoutSlideCollection 유형은 다음 멤버를 노출합니다:

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | 지정된 유형의 첫 번째 레이아웃 슬라이드를 반환합니다.<br/>            찾을 레이아웃 슬라이드의 유형. 지정된 유형과 일치하는 [`LayoutSlide`](/slides/python-net/ko/aspose.slides/layoutslide) 또는 레이아웃이 없으면 None을 반환합니다. |
| [`remove(self, value)`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | 컬렉션에서 레이아웃을 제거합니다. |
| [`remove_unused(self)`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/remove_unused/#) | 사용되지 않는 레이아웃 슬라이드(HasDependingSlides가 false인 레이아웃 슬라이드)를 제거합니다. |
| [`add_clone(self, source_layout)`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | 지정된 레이아웃 슬라이드의 복사본을 컬렉션 끝에 추가합니다. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | 지정된 레이아웃 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | 새 레이아웃 슬라이드를 컬렉션 끝에 추가합니다. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | 새 레이아웃 슬라이드를 컬렉션의 지정된 위치에 삽입합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/remove_at/#int) | 컬렉션의 지정된 인덱스에 있는 요소를 제거합니다. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | 컬렉션에서 레이아웃 슬라이드를 지정된 위치로 이동합니다. |

### 참조
* 클래스 [`LayoutSlideCollection`](/slides/python-net/ko/aspose.slides/layoutslidecollection)
* 클래스 [`MasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)