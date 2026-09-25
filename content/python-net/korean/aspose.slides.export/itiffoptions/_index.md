---
title: ITiffOptions class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/itiffoptions/
---
## ITiffOptions 클래스

프레젠테이션을 TIFF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

ITiffOptions 형식은 다음 멤버를 제공합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`image_size`](/slides/python-net/ko/aspose.slides.export/itiffoptions/image_size/) | 생성된 TIFF 이미지의 크기를 지정합니다.<br/> 기본값은 0x0이며, 이는 생성된 이미지 크기가 프레젠테이션 슬라이드 크기 값을 기반으로 계산된다는 의미입니다.<br/> 읽기/쓰기 [`Size`](/slides/python-net/ko/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/ko/aspose.slides.export/itiffoptions/dpi_x/) | 가로 해상도를 인치당 점(dot)으로 지정합니다.<br/> 읽기/쓰기 **int**. |
| [`dpi_y`](/slides/python-net/ko/aspose.slides.export/itiffoptions/dpi_y/) | 세로 해상도를 인치당 점(dot)으로 지정합니다.<br/> 읽기/쓰기 **int**. |
| [`show_hidden_slides`](/slides/python-net/ko/aspose.slides.export/itiffoptions/show_hidden_slides/) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다.<br/> 기본값은 `false`입니다. |
| [`compression_type`](/slides/python-net/ko/aspose.slides.export/itiffoptions/compression_type/) | 압축 유형을 지정합니다.<br/> 읽기/쓰기 [`TiffCompressionTypes`](/slides/python-net/ko/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ko/aspose.slides.export/itiffoptions/pixel_format/) | 생성된 이미지의 픽셀 형식을 지정합니다.<br/> 읽기/쓰기 [`ImagePixelFormat`](/slides/python-net/ko/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ko/aspose.slides.export/itiffoptions/slides_layout_options/) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다 [`ISlidesLayoutOptions`](/slides/python-net/ko/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ko/aspose.slides.export/itiffoptions/bw_conversion_mode/) | 컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다.<br/> 이 옵션은 [`ITiffOptions.compression_type`](/slides/python-net/ko/aspose.slides.export/itiffoptions/compression_type) <br/> 가 [`TiffCompressionTypes.CCITT4`](/slides/python-net/ko/aspose.slides.export/tiffcompressiontypes/CCITT4) 또는 [`TiffCompressionTypes.CCITT3`](/slides/python-net/ko/aspose.slides.export/tiffcompressiontypes/CCITT3) 로 설정된 경우에만 적용됩니다.<br/> 읽기/쓰기 [`BlackWhiteConversionMode`](/slides/python-net/ko/aspose.slides.export/blackwhiteconversionmode).<br/> 기본값은 [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ko/aspose.slides.export/blackwhiteconversionmode/DEFAULT)입니다. |
| [`ink_options`](/slides/python-net/ko/aspose.slides.export/itiffoptions/ink_options/) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.<br/> 읽기 전용 [`IInkOptions`](/slides/python-net/ko/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### 참고
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)