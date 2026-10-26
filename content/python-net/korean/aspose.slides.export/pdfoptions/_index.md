---
title: PdfOptions class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/pdfoptions/
---
## PdfOptions 클래스

프레젠테이션을 Pdf 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

**상속:**[`PdfOptions`](/slides/python-net/ko/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

PdfOptions 유형은 다음 멤버를 노출합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/pdfoptions/__init__/#) | 기본 생성자. |

## 속성

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/pdfoptions/warning_callback/) | 경고를 수신하고 로드 과정이 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/pdfoptions/progress_callback/) | 저장 진행률을 백분율로 업데이트하는 콜백 객체를 나타냅니다.<br/>            [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback)를 참조하세요. |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/pdfoptions/default_regular_font/) | 소스 폰트를 찾을 수 없을 때 사용되는 폰트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/pdfoptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/pdfoptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. <br/>            읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`slides_layout_options`](/slides/python-net/ko/aspose.slides.export/pdfoptions/slides_layout_options/) | 프레젠테이션 [`ISlidesLayoutOptions`](/slides/python-net/ko/aspose.slides.export/islideslayoutoptions)을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 가져오거나 설정합니다. |
| [`ink_options`](/slides/python-net/ko/aspose.slides.export/pdfoptions/ink_options/) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.<br/>            읽기 전용 [`IInkOptions`](/slides/python-net/ko/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ko/aspose.slides.export/pdfoptions/show_hidden_slides/) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다.<br/>            기본값은 `false` 입니다. |
| [`text_compression`](/slides/python-net/ko/aspose.slides.export/pdfoptions/text_compression/) | 문서의 모든 텍스트 내용에 사용할 압축 유형을 지정합니다.<br/>            읽기/쓰기 [`PdfTextCompression`](/slides/python-net/ko/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/ko/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | 각 이미지에 대해 가장 효율적인 압축(기본 압축 대신)을 자동으로 선택할지 여부를 나타냅니다 <br/>            **bool**.true 로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적절한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다. <br/>            최적 이미지 압축 비율 선택은 계산 비용이 많이 들고 추가 RAM을 사용하며, 이 옵션은 기본값이 **bool**.false 입니다. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/ko/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Aspose.Slides가 ASCII(33..127 코드 범위) 텍스트에 대해 공통 폰트를 포함시킬지 결정합니다.<br/>            127보다 큰 문자 코드는 항상 포함됩니다.<br/>            공통 폰트 목록에는 PDF 기본 14폰트와 사용자가 지정한 추가 폰트가 포함됩니다.<br/>            읽기/쓰기 **bool**. |
| [`additional_common_font_families`](/slides/python-net/ko/aspose.slides.export/pdfoptions/additional_common_font_families/) | Aspose.Slides가 공통으로 간주해야 할 폰트 패밀리의 사용자 정의 이름 배열을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**[]. |
| [`embed_full_fonts`](/slides/python-net/ko/aspose.slides.export/pdfoptions/embed_full_fonts/) | 폰트의 모든 문자를 포함시킬지, 사용된 부분 집합만 포함시킬지 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/ko/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | 폰트가 굵게 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장할지 여부를 나타냅니다.<br/>            이 방법은 특정 폰트에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다.<br/>            읽기/쓰기 **bool**. |
| [`jpeg_quality`](/slides/python-net/ko/aspose.slides.export/pdfoptions/jpeg_quality/) | PDF 문서 내부 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`compliance`](/slides/python-net/ko/aspose.slides.export/pdfoptions/compliance/) | 생성된 PDF 문서의 원하는 호환성 수준을 지정합니다.<br/>            읽기/쓰기 [`PdfCompliance`](/slides/python-net/ko/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/ko/aspose.slides.export/pdfoptions/password/) | PDF 문서를 보호하기 위한 사용자 비밀번호를 설정합니다. <br/>            읽기/쓰기 **str**. |
| [`access_permissions`](/slides/python-net/ko/aspose.slides.export/pdfoptions/access_permissions/) | 문서가 사용자 접근 권한으로 열릴 때 부여할 접근 권한을 지정하는 플래그 집합을 포함합니다.<br/>            [`PdfAccessPermissions`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions)를 참조하세요. |
| [`save_metafiles_as_png`](/slides/python-net/ko/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true 로 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`sufficient_resolution`](/slides/python-net/ko/aspose.slides.export/pdfoptions/sufficient_resolution/) | PDF 문서 내부 이미지의 해상도를 결정하는 값을 반환하거나 설정합니다.<br/>            <br/>속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 줍니다.<br/><br/><br/>기본값은 **96** 입니다.<br/><br/><br/>            읽기/쓰기 **float**. |
| [`draw_slides_frame`](/slides/python-net/ko/aspose.slides.export/pdfoptions/draw_slides_frame/) | 각 슬라이드 주변에 검은색 프레임을 그리려면 true 로 설정합니다.<br/>             읽기/쓰기 **bool**. |
| [`image_transparent_color`](/slides/python-net/ko/aspose.slides.export/pdfoptions/image_transparent_color/) | 이미지 투명 색상을 가져오거나 설정합니다. |
| [`apply_image_transparent`](/slides/python-net/ko/aspose.slides.export/pdfoptions/apply_image_transparent/) | `true`인 경우 지정된 투명 색상을 이미지에 적용합니다. |
| [`include_ole_data`](/slides/python-net/ko/aspose.slides.export/pdfoptions/include_ole_data/) | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true 로 설정합니다.<br/>            읽기/쓰기 **bool**. |


### 참조
* 클래스 [`PdfOptions`](/slides/python-net/ko/aspose.slides.export/pdfoptions)
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)