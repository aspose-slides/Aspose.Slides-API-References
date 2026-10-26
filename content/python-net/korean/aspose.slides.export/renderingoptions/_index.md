---
title: RenderingOptions class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/renderingoptions/
---
## RenderingOptions 클래스

프레젠테이션/슬라이드가 렌더링되는 방식을 제어하는 옵션을 제공합니다.

**Inheritance:**[`RenderingOptions`](/slides/python-net/ko/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

RenderingOptions 유형은 다음 멤버를 노출합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/renderingoptions/__init__/#) | 기본 생성자입니다. |

## 속성

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/renderingoptions/warning_callback/) | 경고를 수신하고 로드 프로세스가 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/renderingoptions/progress_callback/) | 퍼센트 단위로 저장 진행 업데이트를 위한 콜백 객체를 나타냅니다.<br/>            보기 [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/renderingoptions/default_regular_font/) | 소스 글꼴을 찾을 수 없을 경우 사용되는 글꼴을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/renderingoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/renderingoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. 기본값은 **false**입니다. |
| [`slides_layout_options`](/slides/python-net/ko/aspose.slides.export/renderingoptions/slides_layout_options/) | 프레젠테이션 [`ISlidesLayoutOptions`](/slides/python-net/ko/aspose.slides.export/islideslayoutoptions)을(를) 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다. |
| [`ink_options`](/slides/python-net/ko/aspose.slides.export/renderingoptions/ink_options/) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.<br/>            읽기 전용 [`IInkOptions`](/slides/python-net/ko/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/ko/aspose.slides.export/renderingoptions/disable_font_ligatures/) | 텍스트가 리가처를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다.<br/>            `true`로 설정하면 렌더링된 출력에서 리가처가 비활성화됩니다. 기본적으로 이 속성은 `false`로 설정됩니다. |

### 참조
* 클래스 [`RenderingOptions`](/slides/python-net/ko/aspose.slides.export/renderingoptions)
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)