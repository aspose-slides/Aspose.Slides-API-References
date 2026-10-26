---
title: ISlide class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/islide/
---
## ISlide 클래스

프레젠테이션에서 슬라이드를 나타냅니다.

ISlide 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/ko/aspose.slides/islide/header_footer_manager/) | 슬라이드의 HeaderFooter 관리자를 반환합니다.<br/>            읽기 전용 [`ISlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/ko/aspose.slides/islide/slide_number/) | 슬라이드 번호를 반환합니다.<br/>            [`IPresentation.slides`](/slides/python-net/ko/aspose.slides/ipresentation/slides) 컬렉션에서 슬라이드의 인덱스는 항상 SlideNumber - 1과 같습니다.<br/>            읽기/쓰기 **int**. |
| [`hidden`](/slides/python-net/ko/aspose.slides/islide/hidden/) | 지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`layout_slide`](/slides/python-net/ko/aspose.slides/islide/layout_slide/) | 현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/ko/aspose.slides/islide/notes_slide_manager/) | 노트 슬라이드에 접근하고 추가 및 제거할 수 있습니다.<br/>            읽기 전용 [`INotesSlideManager`](/slides/python-net/ko/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/ko/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/ko/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/ko/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/ko/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/ko/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/ko/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/ko/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/ko/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/ko/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/ko/aspose.slides/islide/theme_manager/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/islide/get_image/#float-float) | 맞춤 스케일링이 적용된 이미지 객체를 반환합니다. |
| [`get_image(self)`](/slides/python-net/ko/aspose.slides/islide/get_image/#) | 실제 크기의 20%인 썸네일 이미지 객체를 반환합니다. |
| [`get_image(self, image_size)`](/slides/python-net/ko/aspose.slides/islide/get_image/#asposeslidessize) | 지정된 크기의 이미지 객체를 반환합니다. |
| [`get_image(self, options)`](/slides/python-net/ko/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | 지정된 매개변수로 만든 썸네일 tiff 비트맵 객체를 반환합니다. |
| [`get_image(self, options)`](/slides/python-net/ko/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | 썸네일 비트맵 객체를 반환합니다. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | 맞춤 스케일링이 적용된 썸네일 비트맵 객체를 반환합니다. |
| [`get_image(self, options, image_size)`](/slides/python-net/ko/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | 지정된 크기의 썸네일 비트맵 객체를 반환합니다. |
| [`write_as_svg(self, stream)`](/slides/python-net/ko/aspose.slides/islide/write_as_svg/#iorawiobase) | 슬라이드 내용을 SVG 파일로 저장합니다. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ko/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | 슬라이드 내용을 SVG 파일로 저장합니다. |
| [`get_slide_comments(self, author)`](/slides/python-net/ko/aspose.slides/islide/get_slide_comments/#icommentauthor) | 특정 작성자가 추가한 모든 슬라이드 주석을 반환합니다. |
| [`write_as_emf(self, stream)`](/slides/python-net/ko/aspose.slides/islide/write_as_emf/#iorawiobase) | 슬라이드 내용을 EMF 파일로 저장합니다. |
| [`remove(self)`](/slides/python-net/ko/aspose.slides/islide/remove/#) | 프레젠테이션에서 슬라이드를 제거합니다. |
| [`reset(self)`](/slides/python-net/ko/aspose.slides/islide/reset/#) | LayoutSlide에 프로토타입이 있는 모든 도형의 위치, 크기 및 형식을 재설정합니다. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ko/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/ko/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides/islide/create_theme_effective/#) |  |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)