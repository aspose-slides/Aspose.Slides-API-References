---
title: ISVGOptions class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/isvgoptions/
---
## ISVGOptions 클래스

SVG 옵션을 나타냅니다.

ISVGOptions 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`vectorize_text`](/slides/python-net/ko/aspose.slides.export/isvgoptions/vectorize_text/) | 슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다.<br/>            Read/write **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/ko/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | 메타파일 래스터화에 대한 낮은 해상도 제한을 반환하거나 설정합니다.<br/>            Read/write **int**. |
| [`disable_3d_text`](/slides/python-net/ko/aspose.slides.export/isvgoptions/disable_3d_text/) | SVG에서 3D 텍스트가 비활성화되는지를 결정합니다.<br/>            Read/write **bool**. |
| [`disable_gradient_split`](/slides/python-net/ko/aspose.slides.export/isvgoptions/disable_gradient_split/) | FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다.<br/>            Read/write **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/ko/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 없습니다.<br/>            Aspose.Slides SVG 작성 엔진은 해당 문제에 대한 해결 방법을 제공합니다:<br/>            화살표가 있는 라인의 끝을 잘라서 라인이 마커와 겹치지 않도록 합니다.<br/>            이 옵션은 해당 동작을 끕니다.<br/>            Read/write **bool**. |
| [`jpeg_quality`](/slides/python-net/ko/aspose.slides.export/isvgoptions/jpeg_quality/) | JPEG 인코딩 품질을 결정합니다.<br/>            Read/write **int**. |
| [`shape_formatting_controller`](/slides/python-net/ko/aspose.slides.export/isvgoptions/shape_formatting_controller/) | 사용자가 형태 변환을 제어할 수 있는 콜백 인터페이스를 반환하고 설정합니다.<br/>            Read/write [`ISvgShapeFormattingController`](/slides/python-net/ko/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/ko/aspose.slides.export/isvgoptions/pictures_compression/) | 그림 압축 수준을 나타냅니다<br/>            Read/write [`ISVGOptions.pictures_compression`](/slides/python-net/ko/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/ko/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | 크롭된 부분이 문서의 일부로 남아 있는지를 나타내는 부울 플래그입니다.<br/>            true이면 크롭된 <br/>            부분이 제거되고, false이면 문서에 직렬화됩니다(이는 파일이 커질 수 있습니다).<br/>            Read/write **bool**. |
| [`use_frame_size`](/slides/python-net/ko/aspose.slides.export/isvgoptions/use_frame_size/) | 텍스트 프레임을 렌더링 영역에 포함할지 여부를 결정합니다.<br/>            Read/write **bool**.<br/>            기본값은 false입니다. |
| [`use_frame_rotation`](/slides/python-net/ko/aspose.slides.export/isvgoptions/use_frame_rotation/) | 렌더링 시 지정된 회전을 형태에 적용할지 여부를 결정합니다.<br/>            Read/write **bool**.<br/>            기본값은 true입니다. |
| [`external_fonts_handling`](/slides/python-net/ko/aspose.slides.export/isvgoptions/external_fonts_handling/) | 외부에서 로드된 글꼴을 처리하는 방식을 결정합니다.<br/>            Read/write [`SvgExternalFontsHandling`](/slides/python-net/ko/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/ko/aspose.slides.export/isvgoptions/ink_options/) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.<br/>            Read-only [`IInkOptions`](/slides/python-net/ko/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/ko/aspose.slides.export/isvgoptions/disable_font_ligatures/) | 텍스트가 합자를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다.<br/>            값이 `true`로 설정되면 렌더링된 출력에서 합자가 비활성화됩니다. 기본적으로 이 속성은 `false`로 설정됩니다. |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### 참조
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)