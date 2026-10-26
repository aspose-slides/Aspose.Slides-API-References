---
title: PptxOptions class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/pptxoptions/
---
## PptxOptions 클래스

OpenXml 프레젠테이션(PPTX, PPSX, POTX, PPTM, PPSM, POTM)을 저장하기 위한 옵션을 나타냅니다.

**Inheritance:**[`PptxOptions`](/slides/python-net/ko/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

PptxOptions 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/pptxoptions/__init__/#) | 새 PptxOptions 인스턴스를 생성합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/pptxoptions/warning_callback/) | 경고를 수신하고 로드 프로세스가 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/pptxoptions/progress_callback/) | 백분율로 저장 진행 업데이트를 위한 콜백 객체를 나타냅니다.<br/>            [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback)을(를) 참조하십시오. |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/pptxoptions/default_regular_font/) | 원본 글꼴을 찾을 수 없을 경우 사용되는 글꼴을 반환하거나 설정합니다.<br/>            읽기-쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/pptxoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/pptxoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`conformance`](/slides/python-net/ko/aspose.slides.export/pptxoptions/conformance/) | Presentation 문서가 준수하는 호환성 클래스를 지정합니다.<br/>            기본값은 [`Conformance.ECMA_376_2006`](/slides/python-net/ko/aspose.slides.export/conformance/ECMA_376_2006) 입니다. |
| [`zip_64_mode`](/slides/python-net/ko/aspose.slides.export/pptxoptions/zip_64_mode/) | Presentation 문서에 ZIP64 형식을 사용할지 여부를 지정합니다.<br/>            기본값은 [`Zip64Mode.IF_NECESSARY`](/slides/python-net/ko/aspose.slides.export/zip64mode/IF_NECESSARY) 입니다. |
| [`refresh_thumbnail`](/slides/python-net/ko/aspose.slides.export/pptxoptions/refresh_thumbnail/) | 프레젠테이션 썸네일을 새로 고칠지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**.<br/>            기본값은 **true** 입니다. |
| [`compression_level`](/slides/python-net/ko/aspose.slides.export/pptxoptions/compression_level/) | 프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다.<br/>            기본값은 [`CompressionLevel.LEVEL6`](/slides/python-net/ko/aspose.slides.export/compressionlevel/LEVEL6) 입니다. |

### 참조
* 클래스 [`PptxOptions`](/slides/python-net/ko/aspose.slides.export/pptxoptions)
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)