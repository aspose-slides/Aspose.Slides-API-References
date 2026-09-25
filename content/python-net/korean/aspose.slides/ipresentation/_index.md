---
title: IPresentation class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ipresentation/
---
## IPresentation 클래스

Presentation 문서

IPresentation 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`current_date_time`](/slides/python-net/ko/aspose.slides/ipresentation/current_date_time/) | 날짜 및 시간을 반환하거나 설정합니다. 이 값은 datetime 필드의 내용을 대신합니다.<br/>            기본적으로 이 Presentation 객체가 생성된 시간입니다.<br/>            읽기/쓰기 **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/ko/aspose.slides/ipresentation/header_footer_manager/) | 프레젠테이션의 HeaderFooter 관리자를 반환합니다.<br/>            읽기 전용 [`IPresentationHeaderFooterManager`](/slides/python-net/ko/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/ko/aspose.slides/ipresentation/protection_manager/) | 이 프레젠테이션에 대한 권한 관리자를 가져옵니다. <br/>            읽기 전용 [`IProtectionManager`](/slides/python-net/ko/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/ko/aspose.slides/ipresentation/slides/) | 프레젠테이션에 정의된 모든 슬라이드의 목록을 반환합니다.<br/ko/>            읽기 전용 [`ISlideCollection`](/slides/python-net/ko/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/ko/aspose.slides/ipresentation/sections/) | 프레젠테이션에 정의된 모든 슬라이드 섹션의 목록을 반환합니다.<br/>            읽기 전용 [`ISectionCollection`](/slides/python-net/ko/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/ko/aspose.slides/ipresentation/slide_size/) | 슬라이드 크기 객체를 반환합니다.<br/>            읽기 전용 [`ISlideSize`](/slides/python-net/ko/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/ko/aspose.slides/ipresentation/notes_size/) | 노트 슬라이드 크기 객체를 반환합니다.<br/>            읽기 전용 [`INotesSize`](/slides/python-net/ko/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/ko/aspose.slides/ipresentation/layout_slides/) | 프레젠테이션에 정의된 모든 레이아웃 슬라이드의 목록을 반환합니다.<br/>            읽기 전용 [`IGlobalLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/ko/aspose.slides/ipresentation/masters/) | 프레젠테이션에 정의된 모든 마스터 슬라이드의 목록을 반환합니다.<br/>            읽기 전용 [`IMasterSlideCollection`](/slides/python-net/ko/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/ko/aspose.slides/ipresentation/master_notes_slide_manager/) | 노트 마스터 관리자를 반환합니다.<br/>            읽기 전용 [`IMasterNotesSlideManager`](/slides/python-net/ko/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/ko/aspose.slides/ipresentation/master_handout_slide_manager/) | 핸드아웃 마스터 관리자를 반환합니다.<br/>            읽기 전용 [`IMasterHandoutSlideManager`](/slides/python-net/ko/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/ko/aspose.slides/ipresentation/fonts_manager/) | 글꼴 관리자를 반환합니다.<br/>            읽기 전용 [`IFontsManager`](/slides/python-net/ko/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/ko/aspose.slides/ipresentation/default_text_style/) | 도형의 기본 텍스트 스타일을 반환합니다.<br/>            읽기 전용 [`ITextStyle`](/slides/python-net/ko/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/ko/aspose.slides/ipresentation/comment_authors/) | 댓글 작성자 컬렉션을 반환합니다.<br/>            읽기 전용 [`ICommentAuthorCollection`](/slides/python-net/ko/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/ko/aspose.slides/ipresentation/document_properties/) | 표준 및 사용자 정의 문서 속성을 포함하는 DocumentProperties 객체를 반환합니다.<br/>            읽기 전용 [`IDocumentProperties`](/slides/python-net/ko/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/ko/aspose.slides/ipresentation/images/) | 프레젠테이션에 포함된 모든 이미지의 컬렉션을 반환합니다.<br/>            읽기 전용 [`IImageCollection`](/slides/python-net/ko/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/ko/aspose.slides/ipresentation/audios/) | 프레젠테이션에 포함된 모든 임베디드 오디오 파일의 컬렉션을 반환합니다.<br/>            읽기 전용 [`IAudioCollection`](/slides/python-net/ko/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/ko/aspose.slides/ipresentation/videos/) | 프레젠테이션에 포함된 모든 임베디드 비디오 파일의 컬렉션을 반환합니다.<br/>            읽기 전용 [`IVideoCollection`](/slides/python-net/ko/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/ko/aspose.slides/ipresentation/custom_data/) | 프레젠테이션의 사용자 정의 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/ko/aspose.slides/ipresentation/vba_project/) | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져옵니다.<br/>            읽기/쓰기 [`IVbaProject`](/slides/python-net/ko/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/ko/aspose.slides/ipresentation/source_format/) | 프레젠테이션이 로드된 형식에 대한 정보를 반환합니다.<br/>            읽기 전용 [`IPresentation.source_format`](/slides/python-net/ko/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/ko/aspose.slides/ipresentation/master_theme/) | 프레젠테이션의 마스터 테마를 반환합니다.<br/>            읽기 전용 [`IMasterTheme`](/slides/python-net/ko/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/ipresentation/hyperlink_queries/) | 모든 프레젠테이션 슬라이드(마스터, 레이아웃, 노트 슬라이드 제외)에 포함된 모든 하이퍼링크에 대한 손쉬운 접근을 제공합니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/ko/aspose.slides/ipresentation/view_properties/) | 프레젠테이션 전역 뷰 속성을 가져옵니다.<br/>            읽기 전용 [`IViewProperties`](/slides/python-net/ko/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/ko/aspose.slides/ipresentation/first_slide_number/) | 프레젠테이션에서 첫 슬라이드 번호를 나타냅니다.<br/>            읽기/쓰기 **int**. |
| [`all_custom_xml_parts`](/slides/python-net/ko/aspose.slides/ipresentation/all_custom_xml_parts/) | 프레젠테이션의 모든 사용자 정의 데이터 파트를 반환합니다.<br/>            읽기 전용 [`ICustomXmlPart`](/slides/python-net/ko/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/ko/aspose.slides/ipresentation/digital_signatures/) | 프레젠테이션에 서명하는 데 사용된 서명의 컬렉션을 반환합니다.<br/>            읽기 전용 [`IDigitalSignatureCollection`](/slides/python-net/ko/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/ko/aspose.slides/ipresentation/sensitivity_labels/) | 프레젠테이션 문서에 적용된 민감도 레이블 컬렉션을 반환합니다.<br/>            읽기 전용 [`ISensitivityLabelCollection`](/slides/python-net/ko/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/ko/aspose.slides/ipresentation/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/ko/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장합니다. |
| [`save(self, stream, format)`](/slides/python-net/ko/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [`save(self, fname, format, options)`](/slides/python-net/ko/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 파일에 저장합니다. |
| [`save(self, stream, format, options)`](/slides/python-net/ko/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 스트림에 저장합니다. |
| [`save(self, fname, slides, format)`](/slides/python-net/ko/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | 프레젠테이션의 지정된 슬라이드를 지정된 형식으로 파일에 저장합니다. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/ko/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 프레젠테이션의 지정된 슬라이드를 지정된 형식으로 파일에 저장합니다. |
| [`save(self, stream, slides, format)`](/slides/python-net/ko/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | 프레젠테이션의 지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/ko/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 프레젠테이션의 지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [`save(self, options)`](/slides/python-net/ko/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | 프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합에 저장합니다. |
| [`get_images(self, options)`](/slides/python-net/ko/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| [`get_images(self, options, slides)`](/slides/python-net/ko/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | 프레젠테이션의 지정된 슬라이드에 대한 썸네일 비트맵 객체를 반환합니다. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | 프레젠테이션의 모든 슬라이드에 대해 사용자 정의 스케일링이 적용된 썸네일 이미지 객체를 반환합니다. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/ko/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | 프레젠테이션의 지정된 슬라이드에 대해 사용자 정의 스케일링이 적용된 썸네일 이미지 객체를 반환합니다. |
| [`get_images(self, options, image_size)`](/slides/python-net/ko/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | 프레젠테이션의 모든 슬라이드에 대해 지정된 크기의 썸네일 이미지 객체를 반환합니다. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/ko/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | 프레젠테이션의 지정된 슬라이드에 대해 지정된 크기의 썸네일 이미지 객체를 반환합니다. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/ko/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/ko/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [`get_slide_by_id(self, id)`](/slides/python-net/ko/aspose.slides/ipresentation/get_slide_by_id/#int) | ID로 Slide, MasterSlide 또는 LayoutSlide를 반환합니다. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | 모든 슬라이드의 모든 허용 가능한 도형 내 모든 단락에서 동일한 서식을 가진 런을 결합합니다. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/ko/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | 정규식과 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/ko/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/ko/aspose.slides/ipresentation/replace_regex/#str-str) | 정규식과 일치하는 모든 항목을 지정된 문자열로 교체합니다. |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)