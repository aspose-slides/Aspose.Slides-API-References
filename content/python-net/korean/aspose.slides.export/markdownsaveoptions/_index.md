---
title: MarkdownSaveOptions class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions 클래스

프레젠테이션을 마크다운으로 저장하는 방식을 제어하는 옵션을 나타냅니다.

**상속:**[`MarkdownSaveOptions`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

MarkdownSaveOptions 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/warning_callback/) | 경고를 수신하고 로딩 프로세스가 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/progress_callback/) | 퍼센트 단위로 저장 진행 상황 업데이트를 위한 콜백 객체를 나타냅니다.<br/>            참조 [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/default_regular_font/) | 원본 글꼴을 찾지 못했을 경우 사용되는 글꼴을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. <br/>            읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`export_type`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/export_type/) | 프레젠테이션 변환에 사용할 마크다운 사양을 지정합니다.<br/>            기본값은 `TextOnly`입니다. |
| [`base_path`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/base_path/) | 리소스가 포함된 문서가 저장될 기본 경로를 지정합니다.<br/>            기본값은 애플리케이션의 현재 디렉터리입니다. |
| [`images_save_folder_name`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | 이미지를 저장할 폴더 이름을 지정합니다.<br/>            기본값은 `Images`입니다. |
| [`new_line_type`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/new_line_type/) | 생성된 문서가 새로운 줄을 \\r(Macintosh), \\n(Unix) 또는 \\r\\n(Windows) 중 어떤 형태로 가질지 지정합니다.<br/>            기본값은 `Unix`입니다. |
| [`show_comments`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/show_comments/) | 생성된 문서가 주석을 표시할지 여부를 지정합니다.<br/>            기본값은 `false`입니다. |
| [`show_hidden_slides`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다.<br/>            기본값은 `false`입니다. |
| [`show_slide_number`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/show_slide_number/) | 생성된 문서가 각 슬라이드 번호를 표시할지 여부를 지정합니다.<br/>            기본값은 `false`입니다. |
| [`flavor`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/flavor/) | 프레젠테이션 변환에 사용할 마크다운 사양을 지정합니다.<br/>            기본값은 `Multi-markdown`입니다. |
| [`slide_number_format`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Markdown 출력에서 슬라이드 번호 헤더에 사용되는 형식 문자열을 가져오거나 설정합니다.<br/>            형식 문자열에는 \"{0}\" 자리 표시자가 포함되어야 하며, 내보내기 시 슬라이드 인덱스로 교체됩니다.<br/>            예: \"# Slide {0}\" 은 \"# Slide 1\", \"# Slide 2\" 등으로 변환됩니다. |
| [`handle_repeated_spaces`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | `true`로 설정하면 최종 Markdown 출력에서 빈 줄이나 공백만 있는 줄을 제거합니다.<br/>            기본값은 `false`입니다. |

### 참고
* 클래스 [`MarkdownSaveOptions`](/slides/python-net/ko/aspose.slides.export/markdownsaveoptions)
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)