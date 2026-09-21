---
title: IPdfOptions class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/ipdfoptions/
---
## IPdfOptions 클래스

프레젠테이션을 PDF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

IPdfOptions 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/text_compression/) | 문서의 모든 텍스트 콘텐츠에 사용될 압축 유형을 지정합니다.<br/>            Read/write [`PdfTextCompression`](/slides/python-net/ko/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | 각 이미지에 대해 가장 효과적인 압축(기본 압축 대신)이 자동으로 선택되어야 하는지 여부를 나타냅니다.<br/>            **bool**.true 로 설정하면 프레젠테이션의 모든 이미지에 대해 가장 적합한 압축 알고리즘이 선택되어 결과 PDF 문서의 크기가 작아집니다.<br/>            최적의 이미지 압축 비율 선택은 계산 비용이 많이 들고 추가 메모리를 사용하며, 이 옵션은 기본값으로 **bool**.false 입니다. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | ASCII 문자 32-127에 대한 TrueType 글꼴을 포함하려면 true로 설정합니다.<br/>            127보다 큰 문자 코드는 항상 포함됩니다.<br/>            Read/write **bool**. |
| [`show_hidden_slides`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/show_hidden_slides/) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다.<br/>            기본값은 `false`입니다. |
| [`additional_common_font_families`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Aspose.Slides가 일반적으로 간주해야 하는 사용자 정의 글꼴 패밀리 이름 배열을 반환하거나 설정합니다.<br/>            Read/write **str**[]. |
| [`embed_full_fonts`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/embed_full_fonts/) | 글꼴의 모든 문자를 포함할지 아니면 사용된 부분집합만 포함할지 결정합니다.<br/>            Read/write **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | 글꼴이 굵은 스타일을 지원하지 않을 때 텍스트를 비트맵으로 래스터화하여 PDF에 저장해야 하는지 여부를 나타냅니다.<br/>            이 방법은 특정 글꼴에 대해 결과 PDF의 텍스트 품질을 향상시킬 수 있습니다.<br/>            Read/write **bool**. |
| [`jpeg_quality`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/jpeg_quality/) | PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다.<br/>            Read/write **int**. |
| [`compliance`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/compliance/) | 생성된 PDF 문서에 대한 원하는 적합성 수준을 지정합니다.<br/>            Read/write [`PdfCompliance`](/slides/python-net/ko/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/password/) | PDF 문서를 보호하기 위한 사용자 비밀번호를 설정합니다.<br/>            Read/write **str**. |
| [`access_permissions`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/access_permissions/) | 문서가 사용자 액세스로 열릴 때 부여할 액세스 권한을 지정하는 플래그 집합을 포함합니다.<br/>            [`PdfAccessPermissions`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions)를 참조하십시오. |
| [`save_metafiles_as_png`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | 프레젠테이션에서 사용된 모든 메타파일을 PNG 이미지로 변환하려면 true로 설정합니다.<br/>            Read/write **bool**. |
| [`sufficient_resolution`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/sufficient_resolution/) | PDF 문서 내 이미지 해상도를 결정하는 값을 반환하거나 설정합니다.<br/>            <br/>이 속성은 파일 크기, 내보내기 시간 및 이미지 품질에 영향을 미칩니다.<br/><br/><br/>기본값은 **96**입니다.<br/><br/><br/>            Read/write **float**. |
| [`draw_slides_frame`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/draw_slides_frame/) | 각 슬라이드 주변에 검은 프레임을 그리려면 true로 설정합니다.<br/>            Read/write **bool**. |
| [`slides_layout_options`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/slides_layout_options/) | [`ISlidesLayoutOptions`](/slides/python-net/ko/aspose.slides.export/islideslayoutoptions)을(를) 사용하여 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져오거나 설정합니다. |
| [`image_transparent_color`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/image_transparent_color/) | 이미지 투명 색상을 가져오거나 설정합니다. |
| [`apply_image_transparent`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/apply_image_transparent/) | `true`인 경우 지정된 투명 색상을 이미지에 적용합니다. |
| [`ink_options`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/ink_options/) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.<br/>            Read-only [`IInkOptions`](/slides/python-net/ko/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/include_ole_data/) | 프레젠테이션의 모든 OLE 데이터를 결과 PDF에 포함된 파일로 변환하려면 true로 설정합니다.<br/>            Read/write **bool**. |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### 참고
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)