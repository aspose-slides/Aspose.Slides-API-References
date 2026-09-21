---
title: LayoutSlide class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/layoutslide/
---
## LayoutSlide 클래스

레이아웃 슬라이드를 나타냅니다.

**Inheritance:**[`LayoutSlide`](/slides/python-net/ko/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/ko/aspose.slides/baseslide)

LayoutSlide 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/ko/aspose.slides/layoutslide/shapes/) | 슬라이드의 도형을 반환합니다.<br/>            읽기 전용 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ko/aspose.slides/layoutslide/controls/) | 슬라이드의 ActiveX 컨트롤 컬렉션을 반환합니다.<br/>            읽기 전용 [`IControlCollection`](/slides/python-net/ko/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ko/aspose.slides/layoutslide/name/) | 슬라이드의 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`slide_id`](/slides/python-net/ko/aspose.slides/layoutslide/slide_id/) | 슬라이드의 ID를 반환합니다.<br/>            읽기 전용 **int**. |
| [`custom_data`](/slides/python-net/ko/aspose.slides/layoutslide/custom_data/) | 슬라이드의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ko/aspose.slides/layoutslide/timeline/) | 애니메이션 타임라인 객체를 반환합니다.<br/>            읽기 전용 [`IAnimationTimeLine`](/slides/python-net/ko/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ko/aspose.slides/layoutslide/slide_show_transition/) | 지정된 슬라이드가 슬라이드 쇼 중에 진행되는 방식에 대한 정보를 포함하는 Transition 객체를 반환합니다.<br/>            읽기 전용 [`ISlideShowTransition`](/slides/python-net/ko/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ko/aspose.slides/layoutslide/background/) | 슬라이드 배경을 반환합니다.<br/>            읽기 전용 [`IBackground`](/slides/python-net/ko/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/layoutslide/hyperlink_queries/) | 포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ko/aspose.slides/layoutslide/show_master_shapes/) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`presentation`](/slides/python-net/ko/aspose.slides/layoutslide/presentation/) | IPresentation 인터페이스를 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ko/aspose.slides/layoutslide/header_footer_manager/) | 레이아웃 슬라이드의 HeaderFooter 관리자를 반환합니다.<br/>            읽기 전용 [`ILayoutSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/ko/aspose.slides/layoutslide/placeholder_manager/) | 레이아웃 슬라이드의 플레이스홀더 관리자를 반환합니다.<br/>            읽기 전용 [`ILayoutPlaceholderManager`](/slides/python-net/ko/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/ko/aspose.slides/layoutslide/master_slide/) | 레이아웃의 마스터 슬라이드를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/ko/aspose.slides/layoutslide/theme_manager/) | 오버라이딩 테마 관리자를 반환합니다.<br/>            읽기 전용 [`IOverrideThemeManager`](/slides/python-net/ko/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/ko/aspose.slides/layoutslide/layout_type/) | 이 레이아웃 슬라이드의 레이아웃 유형을 반환합니다.<br/>            읽기 전용 [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/ko/aspose.slides/layoutslide/has_depending_slides/) | 이 레이아웃 슬라이드에 의존하는 슬라이드가 하나라도 존재하면 true를 반환합니다.<br/>            읽기 전용 **bool**. |
| [`drawing_guides`](/slides/python-net/ko/aspose.slides/layoutslide/drawing_guides/) | 레이아웃 슬라이드의 드로잉 가이드 컬렉션을 반환합니다.<br/>            읽기 전용 [`IDrawingGuidesCollection`](/slides/python-net/ko/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ko/aspose.slides/layoutslide/slide/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | 허용되는 모든 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ko/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | 허용되는 모든 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [`equals(self, slide)`](/slides/python-net/ko/aspose.slides/layoutslide/equals/#ibaseslide) | 두 IBaseSlide 인스턴스가 동일한지 여부를 판단합니다.<br/>            반환값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다.<br/>            모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교에서는 고유 식별자 값(예: SlideId) 및 동적 콘텐츠(예: 날짜 플레이스홀더의 현재 날짜 값)는 고려되지 않습니다. |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides/layoutslide/create_theme_effective/#) | 이 슬라이드에 대한 유효한 테마를 반환합니다. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ko/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | 지정된 대체 텍스트를 가진 도형의 첫 번째 발생을 찾습니다. |
| [`remove(self)`](/slides/python-net/ko/aspose.slides/layoutslide/remove/#) | 프레젠테이션에서 레이아웃을 제거합니다. |
| [`get_depending_slides(self)`](/slides/python-net/ko/aspose.slides/layoutslide/get_depending_slides/#) | 이 레이아웃 슬라이드에 의존하는 모든 슬라이드의 배열을 반환합니다. |

### 참고
* 클래스 [`BaseSlide`](/slides/python-net/ko/aspose.slides/baseslide)
* 클래스 [`LayoutSlide`](/slides/python-net/ko/aspose.slides/layoutslide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)