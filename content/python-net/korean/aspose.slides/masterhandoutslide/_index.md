---
title: MasterHandoutSlide class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide 클래스

핸드아웃용 마스터 슬라이드를 나타냅니다.

**상속:**[`MasterHandoutSlide`](/slides/python-net/ko/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/ko/aspose.slides/baseslide)

MasterHandoutSlide 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`shapes`](/slides/python-net/ko/aspose.slides/masterhandoutslide/shapes/) | 슬라이드의 도형을 반환합니다.<br/>            읽기 전용 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ko/aspose.slides/masterhandoutslide/controls/) | 슬라이드의 ActiveX 컨트롤 컬렉션을 반환합니다.<br/>            읽기 전용 [`IControlCollection`](/slides/python-net/ko/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ko/aspose.slides/masterhandoutslide/name/) | 슬라이드의 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`slide_id`](/slides/python-net/ko/aspose.slides/masterhandoutslide/slide_id/) | 슬라이드의 ID를 반환합니다.<br/>            읽기 전용 **int**. |
| [`custom_data`](/slides/python-net/ko/aspose.slides/masterhandoutslide/custom_data/) | 슬라이드의 사용자 지정 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ko/aspose.slides/masterhandoutslide/timeline/) | 애니메이션 타임라인 객체를 반환합니다.<br/>            읽기 전용 [`IAnimationTimeLine`](/slides/python-net/ko/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ko/aspose.slides/masterhandoutslide/slide_show_transition/) | 지정된 슬라이드가 슬라이드 쇼 중에 진행되는 방법에 대한 정보를 포함하는 Transition 객체를 반환합니다.<br/>            읽기 전용 [`ISlideShowTransition`](/slides/python-net/ko/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ko/aspose.slides/masterhandoutslide/background/) | 슬라이드의 배경을 반환합니다.<br/>            읽기 전용 [`IBackground`](/slides/python-net/ko/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/masterhandoutslide/hyperlink_queries/) | 포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ko/aspose.slides/masterhandoutslide/show_master_shapes/) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다.<br/>            마스터 슬라이드 자체에 대해서는 이 속성이 항상 `false`를 반환합니다.<br/>            읽기/쓰기 **bool**. |
| [`presentation`](/slides/python-net/ko/aspose.slides/masterhandoutslide/presentation/) | IPresentation 인터페이스를 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ko/aspose.slides/masterhandoutslide/header_footer_manager/) | 마스터 핸드아웃 슬라이드의 HeaderFooter 관리자를 반환합니다.<br/>            읽기 전용 [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ko/aspose.slides/masterhandoutslide/theme_manager/) | 테마 관리자를 반환합니다.<br/>            읽기 전용 [`IMasterThemeManager`](/slides/python-net/ko/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/ko/aspose.slides/masterhandoutslide/drawing_guides/) | 마스터 핸드아웃 슬라이드용 드로잉 가이드 컬렉션을 반환합니다.<br/>            읽기 전용 [`IDrawingGuidesCollection`](/slides/python-net/ko/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/ko/aspose.slides/masterhandoutslide/slide/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | 모든 허용된 도형의 모든 단락에서 동일한 형식의 런을 결합합니다. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ko/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | 모든 허용된 도형의 모든 단락에서 동일한 형식의 런을 결합합니다. |
| [`equals(self, slide)`](/slides/python-net/ko/aspose.slides/masterhandoutslide/equals/#ibaseslide) | 두 IBaseSlide 인스턴스가 동일한지 여부를 결정합니다.<br/>            반환값은 슬라이드 구조와 정적 콘텐츠를 기반으로 계산됩니다.<br/>            모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일한 경우 두 슬라이드는 동일합니다. 고유 식별자 값(e.g. SlideId) 및 동적 콘텐츠(e.g. 날짜 자리표시자의 현재 날짜 값)는 비교에 포함되지 않습니다. |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides/masterhandoutslide/create_theme_effective/#) | 이 슬라이드에 대한 효과적인 테마를 반환합니다. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ko/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | 지정된 대체 텍스트를 가진 도형의 첫 번째 발생을 찾습니다. |


### 또 보기
* 클래스 [`BaseSlide`](/slides/python-net/ko/aspose.slides/baseslide)
* 클래스 [`MasterHandoutSlide`](/slides/python-net/ko/aspose.slides/masterhandoutslide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)