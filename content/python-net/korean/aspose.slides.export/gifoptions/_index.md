---
title: GifOptions class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/gifoptions/
---
## GifOptions 클래스

GIF 내보내기 옵션을 나타냅니다.

**상속:**[`GifOptions`](/slides/python-net/ko/aspose.slides.export/gifoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

GifOptions 유형은 다음 멤버를 제공합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/gifoptions/__init__/#) | GifOptions 클래스를 새 인스턴스로 초기화합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/gifoptions/warning_callback/) | 경고를 수신하고 로드 프로세스를 계속할지 아니면 중단할지를 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/gifoptions/progress_callback/) | 백분율로 저장 진행 상황 업데이트를 위한 콜백 객체를 나타냅니다.<br/>            참조 [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/gifoptions/default_regular_font/) | 소스 폰트를 찾을 수 없을 때 사용되는 폰트를 반환하거나 설정합니다.<br/>            읽기-쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/gifoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/gifoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`frame_size`](/slides/python-net/ko/aspose.slides.export/gifoptions/frame_size/) | 프레임 크기를 가져오거나 설정합니다. |
| [`export_hidden_slides`](/slides/python-net/ko/aspose.slides.export/gifoptions/export_hidden_slides/) | 숨겨진 슬라이드를 내보낼지 여부를 결정합니다.<br/>            기본값은 false 입니다. |
| [`transition_fps`](/slides/python-net/ko/aspose.slides.export/gifoptions/transition_fps/) | 전환 FPS [frames/sec]를 가져오거나 설정합니다.<br/>            기본값은 25 입니다. |
| [`default_delay`](/slides/python-net/ko/aspose.slides.export/gifoptions/default_delay/) | 기본 지연 시간 [ms]을 가져오거나 설정합니다. 이 값은 [`ISlideShowTransition.advance_after_time`](/slides/python-net/ko/aspose.slides/islideshowtransition/advance_after_time)가 설정되지 않은 경우 사용됩니다.<br/>            기본값은 1000 입니다. |

### 참고
* 클래스 [`GifOptions`](/slides/python-net/ko/aspose.slides.export/gifoptions)
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)