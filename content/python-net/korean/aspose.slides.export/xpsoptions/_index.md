---
title: XpsOptions class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/xpsoptions/
---
## XpsOptions 클래스

프레젠테이션을 XPS 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

**상속:**[`XpsOptions`](/slides/python-net/ko/aspose.slides.export/xpsoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

XpsOptions 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/xpsoptions/__init__/#) | 기본 생성자. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/xpsoptions/warning_callback/) | 반환하거나 설정하는 객체는 경고를 받고 로드 과정이 계속될지 중단될지를 결정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/xpsoptions/progress_callback/) | 백분율로 저장 진행 상황 업데이트를 위한 콜백 객체를 나타냅니다.<br/>            참조 [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/xpsoptions/default_regular_font/) | 소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환하거나 설정합니다.<br/>            읽기-쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/xpsoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/xpsoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`show_hidden_slides`](/slides/python-net/ko/aspose.slides.export/xpsoptions/show_hidden_slides/) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다.<br/>            기본값은 `false`입니다. |
| [`save_metafiles_as_png`](/slides/python-net/ko/aspose.slides.export/xpsoptions/save_metafiles_as_png/) | 프레젠테이션에 사용된 모든 메타 파일을 PNG 이미지로 변환하려면 true로 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`draw_slides_frame`](/slides/python-net/ko/aspose.slides.export/xpsoptions/draw_slides_frame/) | 각 슬라이드 주위에 검은색 프레임을 그리려면 true로 설정합니다.<br/>            읽기/쓰기 **bool**. |

### 참고
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 클래스 [`XpsOptions`](/slides/python-net/ko/aspose.slides.export/xpsoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)