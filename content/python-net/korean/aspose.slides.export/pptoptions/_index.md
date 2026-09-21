---
title: PptOptions class
second_title: Aspose.Slides Python용 .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/pptoptions/
---
## PptOptions 클래스

프레젠테이션을 PPT 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

**상속:**[`PptOptions`](/slides/python-net/ko/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

PptOptions 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/pptoptions/__init__/#) |  |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/pptoptions/warning_callback/) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지를 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/pptoptions/progress_callback/) | 백분율로 저장 진행 상황 업데이트를 위한 콜백 객체를 나타냅니다.<br/>            참조 [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/pptoptions/default_regular_font/) | 원본 글꼴을 찾을 수 없을 때 사용할 글꼴을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/pptoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/pptoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`root_directory_clsid`](/slides/python-net/ko/aspose.slides.export/pptoptions/root_directory_clsid/) | 루트 디렉터리 항목에 저장되는 객체 클래스 GUID(CLSID)를 나타냅니다. 문서 애플리케이션의 COM 활성화에 사용할 수 있습니다.<br/>            기본값은 '64818D11-4F9B-11CF-86EA-00AA00B929E8'이며, 이는 'Microsoft Powerpoint.Slide.8'에 해당합니다. |

### 참고
* 클래스 [`PptOptions`](/slides/python-net/ko/aspose.slides.export/pptoptions)
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)