---
title: MasterSlide class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masterslide/
---
## MasterSlide 클래스

프레젠테이션의 마스터 슬라이드를 나타냅니다.

**상속:**[`MasterSlide`](/slides/python-net/ko/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/ko/aspose.slides/baseslide)

The MasterSlide type exposes the following members:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`shapes`](/slides/python-net/ko/aspose.slides/masterslide/shapes/) | 슬라이드의 도형을 반환합니다.<br/>            읽기 전용 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ko/aspose.slides/masterslide/controls/) | 슬라이드에 있는 ActiveX 컨트롤 컬렉션을 반환합니다.<br/>            읽기 전용 [`IControlCollection`](/slides/python-net/ko/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ko/aspose.slides/masterslide/name/) | 마스터 슬라이드의 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`slide_id`](/slides/python-net/ko/aspose.slides/masterslide/slide_id/) | 슬라이드의 ID를 반환합니다.<br/>            읽기 전용 **int**. |
| [`custom_data`](/slides/python-net/ko/aspose.slides/masterslide/custom_data/) | 슬라이드의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ko/aspose.slides/masterslide/timeline/) | 애니메이션 타임라인 객체를 반환합니다.<br/>            읽기 전용 [`IAnimationTimeLine`](/slides/python-net/ko/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ko/aspose.slides/masterslide/slide_show_transition/) | 전환 객체를 반환합니다.<br/>            지정된 슬라이드가 슬라이드 쇼 중에 어떻게 진행되는지에 대한 정보를 포함합니다.<br/>            읽기 전용 [`ISlideShowTransition`](/slides/python-net/ko/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ko/aspose.slides/masterslide/background/) | 슬라이드의 배경을 반환합니다.<br/>            읽기 전용 [`IBackground`](/slides/python-net/ko/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/masterslide/hyperlink_queries/) | 포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ko/aspose.slides/masterslide/show_master_shapes/) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다.<br/>            마스터 슬라이드 자체에 대해서는 이 속성이 항상 `false`를 반환합니다.<br/>            읽기/쓰기 **bool**. |
| [`presentation`](/slides/python-net/ko/aspose.slides/masterslide/presentation/) | IPresentation 인터페이스를 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ko/aspose.slides/masterslide/header_footer_manager/) | 마스터 슬라이드의 HeaderFooter 관리자를 반환합니다.<br/>            읽기 전용 [`IMasterSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/ko/aspose.slides/masterslide/title_style/) | 제목 텍스트의 스타일을 반환합니다.<br/>            읽기 전용 [`ITextStyle`](/slides/python-net/ko/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/ko/aspose.slides/masterslide/body_style/) | 본문 텍스트의 스타일을 반환합니다.<br/>            읽기 전용 [`ITextStyle`](/slides/python-net/ko/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/ko/aspose.slides/masterslide/other_style/) | 다른 텍스트의 스타일을 반환합니다.<br/>            읽기 전용 [`ITextStyle`](/slides/python-net/ko/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/ko/aspose.slides/masterslide/layout_slides/) | 이 마스터 슬라이드에 대한 자식 레이아웃 슬라이드 컬렉션을 반환합니다.<br/>            읽기 전용 [`IMasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/ko/aspose.slides/masterslide/preserve/) | 해당 마스터를 따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다.<br/>            참고: Aspose.Slides는 사용되지 않은 마스터를 스스로 삭제하지 않으며, 사용되지 않은 마스터를 실제로 제거하려면 **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste** 를 호출하십시오.<br/>            읽기/쓰기 **bool**. |
| [`has_depending_slides`](/slides/python-net/ko/aspose.slides/masterslide/has_depending_slides/) | 이 마스터 슬라이드에 의존하는 슬라이드가 하나라도 존재하면 true를 반환합니다.<br/>            읽기 전용 **bool**. |
| [`theme_manager`](/slides/python-net/ko/aspose.slides/masterslide/theme_manager/) | 테마 관리자를 반환합니다.<br/>            읽기 전용 [`IMasterThemeManager`](/slides/python-net/ko/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/ko/aspose.slides/masterslide/drawing_guides/) | 마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다.<br/>            읽기 전용 [`IDrawingGuidesCollection`](/slides/python-net/ko/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ko/aspose.slides/masterslide/slide/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/masterslide/join_portions_with_same_formatting/#) | 허용되는 모든 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ko/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | 허용되는 모든 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [`equals(self, slide)`](/slides/python-net/ko/aspose.slides/masterslide/equals/#ibaseslide) | 두 IBaseSlide 인스턴스가 동일한지 여부를 결정합니다.<br/>            반환값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다.<br/>            모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교에서는 SlideId와 같은 고유 식별자 값 및 날짜 자리 표시자와 같은 동적 콘텐츠는 고려되지 않습니다. |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides/masterslide/create_theme_effective/#) | 이 슬라이드에 대한 효과적인 테마를 반환합니다. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ko/aspose.slides/masterslide/find_shape_by_alt_text/#str) | 지정된 대체 텍스트를 가진 도형을 처음으로 찾습니다. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/ko/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | 현재 마스터 슬라이드를 기반으로 새 마스터 슬라이드를 생성하고 외부 테마를 적용합니다.<br/>            그리고 만든 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다. |
| [`get_depending_slides(self)`](/slides/python-net/ko/aspose.slides/masterslide/get_depending_slides/#) | 이 마스터 슬라이드에 의존하는 모든 슬라이드의 배열을 반환합니다. |

### 참고
* 클래스 [`BaseSlide`](/slides/python-net/ko/aspose.slides/baseslide)
* 클래스 [`MasterSlide`](/slides/python-net/ko/aspose.slides/masterslide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)