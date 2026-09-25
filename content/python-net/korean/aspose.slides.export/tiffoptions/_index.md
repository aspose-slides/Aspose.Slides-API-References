---
title: TiffOptions class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/tiffoptions/
---
## TiffOptions 클래스

프레젠테이션을 TIFF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

**상속:**[`TiffOptions`](/slides/python-net/ko/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

TiffOptions 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/tiffoptions/__init__/#) | 기본 생성자. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/tiffoptions/warning_callback/) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/tiffoptions/progress_callback/) | 백분율로 저장 진행 업데이트를 위한 콜백 객체를 나타냅니다.<br/>            참조 [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/tiffoptions/default_regular_font/) | 원본 폰트를 찾을 수 없을 경우 사용되는 폰트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/tiffoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/tiffoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`ink_options`](/slides/python-net/ko/aspose.slides.export/tiffoptions/ink_options/) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.<br/>            읽기 전용 [`IInkOptions`](/slides/python-net/ko/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ko/aspose.slides.export/tiffoptions/show_hidden_slides/) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다.<br/>            기본값은 `false`. |
| [`image_size`](/slides/python-net/ko/aspose.slides.export/tiffoptions/image_size/) | 생성된 TIFF 이미지의 크기를 지정합니다.<br/>            기본값은 0x0이며, 이는 이미지 크기가 프레젠테이션 슬라이드 크기를 기준으로 계산된다는 의미입니다.<br/>            읽기/쓰기 [`Size`](/slides/python-net/ko/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/ko/aspose.slides.export/tiffoptions/dpi_x/) | 인치당 점 수로 가로 해상도를 지정합니다.<br/>            읽기/쓰기 **int**. |
| [`dpi_y`](/slides/python-net/ko/aspose.slides.export/tiffoptions/dpi_y/) | 인치당 점 수로 세로 해상도를 지정합니다.<br/>            읽기/쓰기 **int**. |
| [`compression_type`](/slides/python-net/ko/aspose.slides.export/tiffoptions/compression_type/) | 압축 유형을 지정합니다.<br/>            읽기/쓰기 [`TiffCompressionTypes`](/slides/python-net/ko/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ko/aspose.slides.export/tiffoptions/pixel_format/) | 생성된 이미지의 픽셀 형식을 지정합니다.<br/>            읽기/쓰기 [`ImagePixelFormat`](/slides/python-net/ko/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ko/aspose.slides.export/tiffoptions/slides_layout_options/) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [`ISlidesLayoutOptions`](/slides/python-net/ko/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ko/aspose.slides.export/tiffoptions/bw_conversion_mode/) | 컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다.<br/>            이 옵션은 [`TiffOptions.compression_type`](/slides/python-net/ko/aspose.slides.export/tiffoptions/compression_type)가 [`TiffCompressionTypes.CCITT4`](/slides/python-net/ko/aspose.slides.export/tiffcompressiontypes/CCITT4) 또는 [`TiffCompressionTypes.CCITT3`](/slides/python-net/ko/aspose.slides.export/tiffcompressiontypes/CCITT3) 로 설정된 경우에만 적용됩니다.<br/>            읽기/쓰기 [`BlackWhiteConversionMode`](/slides/python-net/ko/aspose.slides.export/blackwhiteconversionmode).<br/>            기본값은 [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ko/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### 참고
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 클래스 [`TiffOptions`](/slides/python-net/ko/aspose.slides.export/tiffoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)