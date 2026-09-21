---
title: SVGOptions class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/svgoptions/
---
## SVGOptions 클래스

SVG 옵션을 나타냅니다.

**상속:**[`SVGOptions`](/slides/python-net/ko/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

SVGOptions 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/svgoptions/__init__/#) | SVGOptions 클래스를 새 인스턴스로 초기화합니다. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/ko/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | 링크 삽입 컨트롤러 객체를 지정하여 SVGOptions 클래스를 새 인스턴스로 초기화합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/svgoptions/warning_callback/) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/svgoptions/progress_callback/) | 백분율로 저장 진행 업데이트를 위한 콜백 객체를 나타냅니다.<br/>            참조 [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/svgoptions/default_regular_font/) | 소스 폰트를 찾을 수 없는 경우에 사용되는 폰트를 반환하거나 설정합니다.<br/>            읽기-쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/svgoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/svgoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`ink_options`](/slides/python-net/ko/aspose.slides.export/svgoptions/ink_options/) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.<br/>            읽기 전용 [`IInkOptions`](/slides/python-net/ko/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/ko/aspose.slides.export/svgoptions/use_frame_size/) | 텍스트 프레임을 렌더링 영역에 포함할지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**.<br/>            기본값은 false 입니다. |
| [`use_frame_rotation`](/slides/python-net/ko/aspose.slides.export/svgoptions/use_frame_rotation/) | 렌더링 시 지정된 회전을 도형에 적용할지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**.<br/>            기본값은 true 입니다. |
| [`vectorize_text`](/slides/python-net/ko/aspose.slides.export/svgoptions/vectorize_text/) | 슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/ko/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | 메타파일 래스터화에 대한 하위 해상도 한계를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`disable_3d_text`](/slides/python-net/ko/aspose.slides.export/svgoptions/disable_3d_text/) | SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`disable_gradient_split`](/slides/python-net/ko/aspose.slides.export/svgoptions/disable_gradient_split/) | FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다.<br/>            읽기/쓰기 **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/ko/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1은 마커에 대한 인셋을 정의하는 기능이 부족합니다.<br/>            Aspose.Slides SVG 작성 엔진은 해당 문제에 대한 해결 방법을 제공합니다:<br/>            선 끝에 화살표가 있는 경우 선이 마커와 겹치지 않도록 잘라냅니다.<br/>            이 옵션은 해당 동작을 끕니다.<br/>            읽기/쓰기 **bool**. |
| [`default`](/slides/python-net/ko/aspose.slides.export/svgoptions/default/) | 기본 설정을 반환합니다.<br/>            읽기 전용 [`SVGOptions`](/slides/python-net/ko/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/ko/aspose.slides.export/svgoptions/simple/) | 가장 간단하고 작은 SVG 파일 생성을 위한 설정을 반환합니다.<br/>            읽기 전용 [`SVGOptions`](/slides/python-net/ko/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/ko/aspose.slides.export/svgoptions/wysiwyg/) | 가장 정확한 SVG 파일 생성을 위한 설정을 반환합니다.<br/>            읽기 전용 [`SVGOptions`](/slides/python-net/ko/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/ko/aspose.slides.export/svgoptions/jpeg_quality/) | JPEG 인코딩 품질을 결정합니다.<br/>            읽기/쓰기 **int**. |
| [`shape_formatting_controller`](/slides/python-net/ko/aspose.slides.export/svgoptions/shape_formatting_controller/) | 사용자가 도형 변환을 제어할 수 있도록 하는 콜백 인터페이스를 반환하고 설정합니다.<br/>            읽기/쓰기 [`ISvgShapeFormattingController`](/slides/python-net/ko/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/ko/aspose.slides.export/svgoptions/pictures_compression/) | 그림 압축 수준을 나타냅니다 |
| [`delete_pictures_cropped_areas`](/slides/python-net/ko/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | 잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. true이면 잘린 <br/>            부분이 제거되고, false이면 문서에 직렬화됩니다(이는 파일 크기가 커질 수 있습니다) |
| [`external_fonts_handling`](/slides/python-net/ko/aspose.slides.export/svgoptions/external_fonts_handling/) | 외부에서 로드된 폰트를 처리하는 방식을 결정합니다.<br/>            읽기/쓰기 [`SvgExternalFontsHandling`](/slides/python-net/ko/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/ko/aspose.slides.export/svgoptions/disable_font_ligatures/) | 텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            `true`로 설정하면 렌더링 결과에서 합자가 비활성화됩니다. 기본적으로 이 속성은 `false`로 설정됩니다. |


### 참조
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 클래스 [`SVGOptions`](/slides/python-net/ko/aspose.slides.export/svgoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)