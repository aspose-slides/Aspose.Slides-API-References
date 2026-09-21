---
title: HtmlOptions class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.export/htmloptions/
---
## HtmlOptions 클래스

HTML 내보내기 옵션을 나타냅니다.

**상속:**[`HtmlOptions`](/slides/python-net/ko/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)

HtmlOptions 유형은 다음 멤버를 제공합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/ko/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | 콜백을 지정하는 새로운 HtmlOptions 객체를 생성합니다. |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.export/htmloptions/__init__/#) | 단일 HTML 파일에 저장하기 위한 새로운 HtmlOptions 객체를 생성합니다. |

## 속성

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/ko/aspose.slides.export/htmloptions/warning_callback/) | 경고를 수신하고 로드 프로세스가 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ko/aspose.slides.export/htmloptions/progress_callback/) | 백분율로 저장 진행 업데이트를 위한 콜백 객체를 나타냅니다.<br/>            참조 [`IProgressCallback`](/slides/python-net/ko/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides.export/htmloptions/default_regular_font/) | 원본 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`gradient_style`](/slides/python-net/ko/aspose.slides.export/htmloptions/gradient_style/) | 그라디언트의 시각적 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`GradientStyle`](/slides/python-net/ko/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ko/aspose.slides.export/htmloptions/skip_java_script_links/) | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛰는지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. 기본값은 **false** 입니다. |
| [`slides_layout_options`](/slides/python-net/ko/aspose.slides.export/htmloptions/slides_layout_options/) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 반환하거나 설정합니다 [`ISlidesLayoutOptions`](/slides/python-net/ko/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/ko/aspose.slides.export/htmloptions/ink_options/) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다.<br/>            읽기 전용 [`IInkOptions`](/slides/python-net/ko/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ko/aspose.slides.export/htmloptions/show_hidden_slides/) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다.<br/>            기본값은 `false`. |
| [`html_formatter`](/slides/python-net/ko/aspose.slides.export/htmloptions/html_formatter/) | HTML 템플릿을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IHtmlFormatter`](/slides/python-net/ko/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/ko/aspose.slides.export/htmloptions/disable_font_ligatures/) | 텍스트가 합자(ligature)를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 반환하거나 설정합니다.<br/>            값이 `true`로 설정되면 렌더링 출력에서 합자가 비활성화됩니다. 기본적으로 이 속성은 `false`로 설정됩니다. |
| [`slide_image_format`](/slides/python-net/ko/aspose.slides.export/htmloptions/slide_image_format/) | 슬라이드 이미지 형식 옵션을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`ISlideImageFormat`](/slides/python-net/ko/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/ko/aspose.slides.export/htmloptions/jpeg_quality/) | PDF 문서 내 JPEG 이미지의 품질을 결정하는 값을 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`pictures_compression`](/slides/python-net/ko/aspose.slides.export/htmloptions/pictures_compression/) | 그림 압축 수준을 나타냅니다 |
| [`delete_pictures_cropped_areas`](/slides/python-net/ko/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | 잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 불리언 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화됩니다(이는 파일 크기가 커질 수 있습니다) |
| [`svg_responsive_layout`](/slides/python-net/ko/aspose.slides.export/htmloptions/svg_responsive_layout/) | svg 컨테이너에서 너비와 높이 속성을 제외하려면 true - 레이아웃을 반응형으로 만듭니다. 그렇지 않으면 false.<br/>            읽기/쓰기 **bool**. |

### 참고
* 클래스 [`HtmlOptions`](/slides/python-net/ko/aspose.slides.export/htmloptions)
* 클래스 [`SaveOptions`](/slides/python-net/ko/aspose.slides.export/saveoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)