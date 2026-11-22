---
title: Presentation class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/presentation/
---
## Presentation 클래스

Microsoft PowerPoint 프레젠테이션을 나타냅니다.

Presentation 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides/presentation/__init__/#) | 이 생성자는 새 프레젠테이션을 처음부터 만듭니다.<br/>            생성된 프레젠테이션에는 빈 슬라이드가 하나 있습니다. |
| [`__init__(self, load_options)`](/slides/python-net/ko/aspose.slides/presentation/__init__/#loadoptions) | 이 생성자는 새 프레젠테이션을 처음부터 만듭니다.<br/>            생성된 프레젠테이션에는 빈 슬라이드가 하나 있습니다. |
| [`__init__(self, stream)`](/slides/python-net/ko/aspose.slides/presentation/__init__/#iorawiobase) | 이 생성자는 기존 Presentation을 읽기 위한 기본 메커니즘입니다. |
| [`__init__(self, stream, load_options)`](/slides/python-net/ko/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | 이 생성자는 기존 Presentation을 읽기 위한 기본 메커니즘입니다. |
| [`__init__(self, file)`](/slides/python-net/ko/aspose.slides/presentation/__init__/#str) | 이 생성자는 다음으로부터 소스 파일 경로를 가져옵니다.<br/>             Presentation의 내용이 읽혀집니다. |
| [`__init__(self, file, load_options)`](/slides/python-net/ko/aspose.slides/presentation/__init__/#str-loadoptions) | 이 생성자는 다음으로부터 소스 파일 경로를 가져옵니다.<br/>            Presentation의 내용이 읽혀집니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`current_date_time`](/slides/python-net/ko/aspose.slides/presentation/current_date_time/) | 날짜와 시간을 반환하거나 설정합니다. 이 값은 datetime 필드의 내용을 대체합니다.<br/>            기본적으로 이 Presentation 객체 생성 시각입니다.<br/>            읽기/쓰기 **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ko/aspose.slides/presentation/header_footer_manager/) | 실제 HeaderFooter 관리자를 반환합니다.<br/>            읽기 전용 [`IPresentationHeaderFooterManager`](/slides/python-net/ko/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ko/aspose.slides/presentation/protection_manager/) | 이 프레젠테이션에 대한 권한 관리자를 가져옵니다.<br/>            읽기 전용 [`IProtectionManager`](/slides/python-net/ko/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ko/aspose.slides/presentation/slides/) | 프레젠테이션에 정의된 모든 슬라이드의 목록을 반환합니다.<br/ko/>            읽기 전용 [`ISlideCollection`](/slides/python-net/ko/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ko/aspose.slides/presentation/sections/) | 프레젠테이션에 정의된 모든 슬라이드 섹션의 목록을 반환합니다.<br/>            읽기 전용 [`ISectionCollection`](/slides/python-net/ko/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ko/aspose.slides/presentation/slide_size/) | 슬라이드 크기 객체를 반환합니다.<br/>            읽기 전용 [`ISlideSize`](/slides/python-net/ko/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ko/aspose.slides/presentation/notes_size/) | 노트 슬라이드 크기 객체를 반환합니다.<br/>            읽기 전용 [`INotesSize`](/slides/python-net/ko/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ko/aspose.slides/presentation/layout_slides/) | 프레젠테이션에 정의된 모든 레이아웃 슬라이드의 목록을 반환합니다.<br/>            읽기 전용 [`IGlobalLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ko/aspose.slides/presentation/masters/) | 프레젠테이션에 정의된 모든 마스터 슬라이드의 목록을 반환합니다.<br/>            읽기 전용 [`IMasterSlideCollection`](/slides/python-net/ko/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ko/aspose.slides/presentation/master_notes_slide_manager/) | 노트 마스터 관리자를 반환합니다.<br/>            읽기 전용 [`IMasterNotesSlideManager`](/slides/python-net/ko/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ko/aspose.slides/presentation/master_handout_slide_manager/) | 핸드아웃 마스터 관리자를 반환합니다.<br/>            읽기 전용 [`IMasterHandoutSlideManager`](/slides/python-net/ko/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ko/aspose.slides/presentation/fonts_manager/) | 폰트 관리자를 반환합니다.<br/>            읽기 전용 [`IFontsManager`](/slides/python-net/ko/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ko/aspose.slides/presentation/default_text_style/) | 도형에 대한 기본 텍스트 스타일을 반환합니다.<br/>            읽기 전용 [`ITextStyle`](/slides/python-net/ko/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ko/aspose.slides/presentation/comment_authors/) | 댓글 작성자들의 컬렉션을 반환합니다.<br/>            읽기 전용 [`ICommentAuthorCollection`](/slides/python-net/ko/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ko/aspose.slides/presentation/document_properties/) | 표준 및 사용자 정의 문서 속성을 포함하는 DocumentProperties 객체를 반환합니다.<br/>            읽기 전용 [`IDocumentProperties`](/slides/python-net/ko/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ko/aspose.slides/presentation/images/) | 프레젠테이션에 포함된 모든 이미지의 컬렉션을 반환합니다.<br/>            읽기 전용 [`IImageCollection`](/slides/python-net/ko/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ko/aspose.slides/presentation/audios/) | 프레젠테이션에 포함된 모든 임베디드 오디오 파일의 컬렉션을 반환합니다.<br/>            읽기 전용 [`IAudioCollection`](/slides/python-net/ko/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ko/aspose.slides/presentation/videos/) | 프레젠테이션에 포함된 모든 임베디드 비디오 파일의 컬렉션을 반환합니다.<br/>            읽기 전용 [`IVideoCollection`](/slides/python-net/ko/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/ko/aspose.slides/presentation/slide_show_settings/) | 프레젠테이션의 슬라이드 쇼 설정을 반환합니다. |
| [`digital_signatures`](/slides/python-net/ko/aspose.slides/presentation/digital_signatures/) | 프레젠테이션에 서명하는 데 사용된 서명의 컬렉션을 반환합니다.<br/>            읽기 전용 [`IDigitalSignatureCollection`](/slides/python-net/ko/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/presentation/custom_data/) | 프레젠테이션의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/ko/aspose.slides/presentation/all_custom_xml_parts/) | 프레젠테이션의 모든 사용자 정의 데이터 파트를 반환합니다.<br/>            읽기 전용 [`ICustomXmlPart`](/slides/python-net/ko/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/ko/aspose.slides/presentation/vba_project/) | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IVbaProject`](/slides/python-net/ko/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/presentation/hyperlink_queries/) | 모든 프레젠테이션 슬라이드(마스터, 레이아웃, 노트 슬라이드 제외)에 포함된 모든 하이퍼링크에 쉽게 접근할 수 있도록 제공합니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ko/aspose.slides/presentation/view_properties/) | 프레젠테이션 전체 뷰 속성을 가져옵니다.<br/>            읽기 전용 [`IViewProperties`](/slides/python-net/ko/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ko/aspose.slides/presentation/first_slide_number/) | 프레젠테이션에서 첫 번째 슬라이드 번호를 나타냅니다 |
| [`sensitivity_labels`](/slides/python-net/ko/aspose.slides/presentation/sensitivity_labels/) | 프레젠테이션 문서에 적용된 민감도 레이블의 컬렉션을 반환합니다.<br/>            읽기 전용 [`ISensitivityLabelCollection`](/slides/python-net/ko/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/ko/aspose.slides/presentation/source_format/) | 프레젠테이션이 로드된 형식에 관한 정보를 반환합니다.<br/>            읽기 전용 [`SourceFormat`](/slides/python-net/ko/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/ko/aspose.slides/presentation/master_theme/) | 마스터 테마를 반환합니다.<br/>            읽기 전용 [`IMasterTheme`](/slides/python-net/ko/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/ko/aspose.slides/presentation/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ko/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장합니다. |
| [`save(self, stream, format)`](/slides/python-net/ko/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [`save(self, fname, format, options)`](/slides/python-net/ko/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/ko/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 스트림에 저장합니다. |
| [`save(self, options)`](/slides/python-net/ko/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | 프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 세트에 저장합니다. |
| [`save(self, fname, slides, format)`](/slides/python-net/ko/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | 지정된 슬라이드를 페이지 번호를 유지한 채 지정된 형식으로 파일에 저장합니다. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ko/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 지정된 슬라이드를 페이지 번호를 유지한 채 지정된 형식으로 파일에 저장합니다. |
| [`save(self, stream, slides, format)`](/slides/python-net/ko/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | 지정된 슬라이드를 페이지 번호를 유지한 채 지정된 형식으로 스트림에 저장합니다. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ko/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 지정된 슬라이드를 페이지 번호를 유지한 채 지정된 형식으로 스트림에 저장합니다. |
| [`get_images(self, options)`](/slides/python-net/ko/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | 프레젠테이션의 모든 슬라이드에 대한 Image 객체를 반환합니다. |
| [`get_images(self, options, slides)`](/slides/python-net/ko/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | 사용자 지정 스케일링으로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | 사용자 지정 스케일링으로 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [`get_images(self, options, image_size)`](/slides/python-net/ko/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | 지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ko/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | 지정된 크기로 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ko/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ko/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [`get_slide_by_id(self, id)`](/slides/python-net/ko/aspose.slides/presentation/get_slide_by_id/#int) | Id로 Slide, MasterSlide 또는 LayoutSlide를 반환합니다. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/presentation/join_portions_with_same_formatting/#) | 모든 슬라이드의 모든 허용 가능한 도형 내 모든 단락에서 동일한 서식의 런을 결합합니다. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ko/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | 정규 표현식과 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ko/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ko/aspose.slides/presentation/replace_regex/#str-str) | 정규 표현식과 일치하는 모든 항목을 지정된 문자열로 교체합니다. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/ko/aspose.slides/presentation/refresh_charts_data/#bool) | 프레젠테이션의 모든 차트 데이터를 원본 워크북에서 다시 로드합니다. |

### 참조
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)