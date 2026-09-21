---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection class

프레젠테이션의 모든 레이아웃 슬라이드 컬렉션을 나타냅니다.  
LayoutSlideCollection 클래스를 확장하여 마스터 레이아웃 슬라이드의 개별 컬렉션을 통합하는 컨텍스트에서 레이아웃 슬라이드를 추가/복제하는 메서드를 제공합니다.

**Inheritance:**[`GlobalLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/ko/aspose.slides/layoutslidecollection)

GlobalLayoutSlideCollection 타입은 다음 멤버를 노출합니다:

## Indexer

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Methods

| 메서드 | 설명 |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | 지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | 지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다. |
| [`get_by_type(self, type)`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | 지정된 유형의 첫 번째 레이아웃 슬라이드를 반환합니다.<br/>            찾을 레이아웃 슬라이드의 유형.[`LayoutSlide`](/slides/python-net/ko/aspose.slides/layoutslide) 지정된 유형과 일치하는 레이아웃이 없으면 None을 반환합니다. |
| [`remove(self, value)`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | 컬렉션에서 레이아웃을 제거합니다. |
| [`remove_unused(self)`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection/remove_unused/#) | 사용되지 않는 레이아웃 슬라이드(HasDependingSlides가 false인 레이아웃 슬라이드)를 제거합니다. |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | 새 레이아웃 슬라이드를 프레젠테이션에 추가합니다. |

### 참조
* 클래스 [`GlobalLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection)
* 클래스 [`LayoutSlideCollection`](/slides/python-net/ko/aspose.slides/layoutslidecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)