---
title: IMasterSlide class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/imasterslide/
---
## IMasterSlide 클래스

프레젠테이션의 마스터 슬라이드를 나타냅니다.

IMasterSlide 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/ko/aspose.slides/imasterslide/header_footer_manager/) | 마스터 슬라이드의 HeaderFooter 관리자를 반환합니다.<br/>            읽기 전용 [`IMasterSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/ko/aspose.slides/imasterslide/title_style/) | 제목 텍스트의 스타일을 반환합니다.<br/>            읽기 전용 [`ITextStyle`](/slides/python-net/ko/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/ko/aspose.slides/imasterslide/body_style/) | 본문 텍스트의 스타일을 반환합니다.<br/>            읽기 전용 [`ITextStyle`](/slides/python-net/ko/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/ko/aspose.slides/imasterslide/other_style/) | 다른 텍스트의 스타일을 반환합니다.<br/>            읽기 전용 [`ITextStyle`](/slides/python-net/ko/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/ko/aspose.slides/imasterslide/layout_slides/) | 이 마스터 슬라이드에 대한 자식 레이아웃 슬라이드 컬렉션을 반환합니다.<br/>            읽기 전용 [`IMasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/ko/aspose.slides/imasterslide/preserve/) | 해당 마스터를 따르는 모든 슬라이드가 삭제될 때 마스터도 삭제되는지 결정합니다.<br/>            참고: Aspose.Slides는 사용되지 않는 마스터를 자동으로 제거하지 않으며,<br/>            사용되지 않는 마스터를 실제로 제거하려면 **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            읽기/쓰기 **bool**. |
| [`has_depending_slides`](/slides/python-net/ko/aspose.slides/imasterslide/has_depending_slides/) | 이 마스터 슬라이드에 종속되는 슬라이드가 하나 이상 존재하면 true를 반환합니다.<br/>            읽기 전용 **bool**. |
| [`drawing_guides`](/slides/python-net/ko/aspose.slides/imasterslide/drawing_guides/) | 마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다.<br/>            읽기 전용 [`IDrawingGuidesCollection`](/slides/python-net/ko/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/ko/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/ko/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/ko/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/ko/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/ko/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/ko/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/ko/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/ko/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/ko/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/ko/aspose.slides/imasterslide/theme_manager/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/ko/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | 현재 마스터 슬라이드를 기반으로 새 마스터 슬라이드를 생성하고 외부 테마를 적용한 후, 생성된 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다. |
| [`get_depending_slides(self)`](/slides/python-net/ko/aspose.slides/imasterslide/get_depending_slides/#) | 이 마스터 슬라이드에 종속되는 모든 슬라이드의 배열을 반환합니다. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ko/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/ko/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides/imasterslide/create_theme_effective/#) |  |


### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)