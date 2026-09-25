---
title: Slide class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/slide/
---
## Slide 클래스

프레젠테이션의 슬라이드를 나타냅니다.

**상속:**[`Slide`](/slides/python-net/ko/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/ko/aspose.slides/baseslide)

Slide 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/ko/aspose.slides/slide/shapes/) | 슬라이드의 모양을 반환합니다.<br/>            읽기 전용 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ko/aspose.slides/slide/controls/) | 슬라이드의 ActiveX 컨트롤 컬렉션을 반환합니다.<br/>            읽기 전용 [`IControlCollection`](/slides/python-net/ko/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ko/aspose.slides/slide/name/) | 슬라이드의 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`slide_id`](/slides/python-net/ko/aspose.slides/slide/slide_id/) | 슬라이드의 ID를 반환합니다.<br/>            읽기 전용 **int**. |
| [`custom_data`](/slides/python-net/ko/aspose.slides/slide/custom_data/) | 슬라이드의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ko/aspose.slides/slide/timeline/) | 애니메이션 타임라인 객체를 반환합니다.<br/>            읽기 전용 [`IAnimationTimeLine`](/slides/python-net/ko/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ko/aspose.slides/slide/slide_show_transition/) | Transition 객체를 반환합니다.<br/>            지정된 슬라이드가 슬라이드 쇼 중에 어떻게 진행되는지에 대한 정보를 포함합니다.<br/>            읽기 전용 [`ISlideShowTransition`](/slides/python-net/ko/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ko/aspose.slides/slide/background/) | 슬라이드의 배경을 반환합니다.<br/>            읽기 전용 [`IBackground`](/slides/python-net/ko/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/slide/hyperlink_queries/) | 포함된 하이퍼링크에 대한 간편한 접근을 제공합니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ko/aspose.slides/slide/show_master_shapes/) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`presentation`](/slides/python-net/ko/aspose.slides/slide/presentation/) | IPresentation 인터페이스를 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/ko/aspose.slides/slide/header_footer_manager/) | 슬라이드의 HeaderFooter 관리자를 반환합니다.<br/>            읽기 전용 [`ISlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/ko/aspose.slides/slide/theme_manager/) | 우선 적용되는 테마 관리자를 반환합니다.<br/>            읽기 전용 [`IOverrideThemeManager`](/slides/python-net/ko/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/ko/aspose.slides/slide/slide_number/) | 슬라이드 번호를 반환합니다.<br/>            [`Presentation.slides`](/slides/python-net/ko/aspose.slides/presentation/slides) 컬렉션에서 슬라이드의 인덱스는 항상 SlideNumber - Presentation.FirstSlideNumber와 같습니다.<br/>            읽기/쓰기 **int**. |
| [`hidden`](/slides/python-net/ko/aspose.slides/slide/hidden/) | 지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`layout_slide`](/slides/python-net/ko/aspose.slides/slide/layout_slide/) | 현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/ko/aspose.slides/slide/notes_slide_manager/) | 노트 슬라이드에 접근하고, 추가 및 제거할 수 있도록 합니다.<br/>            읽기 전용 [`INotesSlideManager`](/slides/python-net/ko/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/ko/aspose.slides/slide/slide/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/slide/join_portions_with_same_formatting/#) | 모든 허용 가능한 도형의 모든 단락에서 동일한 서식을 가진 실행(run)을 병합합니다. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ko/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | 모든 허용 가능한 도형의 모든 단락에서 동일한 서식을 가진 실행(run)을 병합합니다. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/slide/get_image/#float-float) | 사용자 정의 스케일링이 적용된 썸네일 이미지 객체를 반환합니다. |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/slide/get_image/#) | 실제 크기의 20%인 썸네일 이미지 객체를 반환합니다. |
| [`get_image(self, image_size)`](/slides/python-net/ko/aspose.slides/slide/get_image/#asposeslidessize) | 지정된 크기의 썸네일 이미지 객체를 반환합니다. |
| [`get_image(self, options)`](/slides/python-net/ko/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | 지정된 매개변수를 사용한 썸네일 TIFF 이미지 객체를 반환합니다. |
| [`get_image(self, options)`](/slides/python-net/ko/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | 썸네일 이미지 객체를 반환합니다. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | 사용자 정의 스케일링이 적용된 썸네일 이미지 객체를 반환합니다. |
| [`get_image(self, options, image_size)`](/slides/python-net/ko/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | 지정된 크기의 썸네일 이미지 객체를 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/slide/write_as_svg/#iorawiobase) | 슬라이드 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 슬라이드 내용을 SVG 파일로 저장합니다. |
| [`equals(self, slide)`](/slides/python-net/ko/aspose.slides/slide/equals/#ibaseslide) | 두 IBaseSlide 인스턴스가 동일한지 여부를 결정합니다.<br/>            반환 값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다.<br/>            모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일하다고 판단합니다. 비교에서는 SlideId와 같은 고유 식별자값이나 날짜 자리표시자와 같은 동적 콘텐츠는 고려되지 않습니다. |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides/slide/create_theme_effective/#) | 이 슬라이드에 대한 실제 테마를 반환합니다. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ko/aspose.slides/slide/find_shape_by_alt_text/#str) | 지정된 대체 텍스트를 가진 도형의 첫 번째 발생을 찾습니다. |
| [`write_as_emf(self, stream)`](/slides/python-net/ko/aspose.slides/slide/write_as_emf/#iorawiobase) | 슬라이드 내용을 EMF 파일로 저장합니다. |
| [`remove(self)`](/slides/python-net/ko/aspose.slides/slide/remove/#) | 프레젠테이션에서 슬라이드를 제거합니다. |
| [`reset(self)`](/slides/python-net/ko/aspose.slides/slide/reset/#) | LayoutSlide에 프로토타입이 있는 모든 도형의 위치, 크기 및 서식을 재설정합니다. |
| [`get_slide_comments(self, author)`](/slides/python-net/ko/aspose.slides/slide/get_slide_comments/#icommentauthor) | 특정 작성자가 추가한 모든 슬라이드 주석을 반환합니다. |

### 참고
* 클래스 [`BaseSlide`](/slides/python-net/ko/aspose.slides/baseslide)
* 클래스 [`Slide`](/slides/python-net/ko/aspose.slides/slide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)