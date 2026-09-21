---
title: SwfOptions class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/swfoptions/
---
## SwfOptions 클래스

프레젠테이션을 Swf 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

**상속:**[`SwfOptions`](/slides/python-net/ko/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

SwfOptions 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/swfoptions/__init__/#) | 기본 생성자. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/swfoptions/warning_callback/) | 경고를 수신하고 로드 프로세스가 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다.<br/>읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/swfoptions/progress_callback/) | 백분율로 저장 진행 상태를 업데이트하는 콜백 객체를 나타냅니다.<br/>참조 [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/swfoptions/default_regular_font/) | 소스 폰트를 찾을 수 없을 경우 사용되는 폰트를 반환하거나 설정합니다.<br/>읽기-쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/swfoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/swfoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다.<br/>읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`show_hidden_slides`](/slides/python-net/ko/aspose.slides.export/swfoptions/show_hidden_slides/) | 생성된 문서에 숨김 슬라이드를 포함할지 여부를 지정합니다.<br/>기본값은 `false`입니다. |
| [`compressed`](/slides/python-net/ko/aspose.slides.export/swfoptions/compressed/) | 생성된 SWF 문서를 압축할지 여부를 지정합니다.<br/>기본값은 `true`입니다. |
| [`viewer_included`](/slides/python-net/ko/aspose.slides.export/swfoptions/viewer_included/) | 생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다.<br/>기본값은 `true`입니다. |
| [`show_page_border`](/slides/python-net/ko/aspose.slides.export/swfoptions/show_page_border/) | 페이지 주변 테두리를 표시할지 여부를 지정합니다. 기본값은 true입니다. |
| [`show_full_screen`](/slides/python-net/ko/aspose.slides.export/swfoptions/show_full_screen/) | 전체 화면 버튼을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| [`show_page_stepper`](/slides/python-net/ko/aspose.slides.export/swfoptions/show_page_stepper/) | 페이지 스테퍼를 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| [`show_search`](/slides/python-net/ko/aspose.slides.export/swfoptions/show_search/) | 검색 섹션을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| [`show_top_pane`](/slides/python-net/ko/aspose.slides.export/swfoptions/show_top_pane/) | 전체 상단 패널을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| [`show_bottom_pane`](/slides/python-net/ko/aspose.slides.export/swfoptions/show_bottom_pane/) | 하단 패널을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| [`show_left_pane`](/slides/python-net/ko/aspose.slides.export/swfoptions/show_left_pane/) | 왼쪽 패널을 표시하거나 숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| [`start_open_left_pane`](/slides/python-net/ko/aspose.slides.export/swfoptions/start_open_left_pane/) | 왼쪽 패널을 열린 상태로 시작합니다. flashvars에서 재정의할 수 있습니다. 기본값은 false입니다. |
| [`enable_context_menu`](/slides/python-net/ko/aspose.slides.export/swfoptions/enable_context_menu/) | 컨텍스트 메뉴를 활성화하거나 비활성화합니다. 기본값은 true입니다. |
| [`logo_image_bytes`](/slides/python-net/ko/aspose.slides.export/swfoptions/logo_image_bytes/) | 뷰어의 오른쪽 상단 모서리에 로고로 표시될 이미지입니다.<br/>이미지는 32x64 픽셀 PNG 이미지여야 하며, 그렇지 않을 경우 로고가 올바르게 표시되지 않을 수 있습니다. |
| [`logo_link`](/slides/python-net/ko/aspose.slides.export/swfoptions/logo_link/) | 로고의 전체 하이퍼링크 주소를 가져오거나 설정합니다.<br/>[`SwfOptions.logo_image_bytes`](/slides/python-net/ko/aspose.slides.export/swfoptions/logo_image_bytes)이 지정된 경우에만 효과가 있습니다. |
| [`jpeg_quality`](/slides/python-net/ko/aspose.slides.export/swfoptions/jpeg_quality/) | JPEG 이미지의 품질을 지정합니다.<br/>기본값은 95입니다. |
| [`slides_layout_options`](/slides/python-net/ko/aspose.slides.export/swfoptions/slides_layout_options/) | 프레젠테이션 [`ISlidesLayoutOptions`](/slides/python-net/ko/aspose.slides.export/islideslayoutoptions)을(를) 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다.<br/>이 속성은 [`HandoutLayoutingOptions`](/slides/python-net/ko/aspose.slides.export/handoutlayoutingoptions) 유형의 객체 할당을 지원하지 않습니다. |

### 참고
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 클래스 [`SwfOptions`](/slides/python-net/ko/aspose.slides.export/swfoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)