---
title: IPresentation
second_title: Aspose.Sildes for .NET API 참조
description: 프레젠테이션 문서
type: docs
weight: 6750
url: /ko/aspose.slides/ipresentation/
---
## IPresentation 인터페이스

프레젠테이션 문서

```csharp
public interface IPresentation : IDisposable, IPPresentationComponent
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | 프레젠테이션에 있는 모든 사용자 정의 데이터 파트를 반환합니다. 읽기 전용 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | IDisposable 인터페이스를 반환합니다. 읽기 전용 IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | 기본 IPresentationComponent 인터페이스를 가져올 수 있습니다. 읽기 전용 [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | 프레젠테이션에 포함된 모든 임베디드 오디오 파일의 컬렉션을 반환합니다. 읽기 전용 [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | 코멘트 작성자 컬렉션을 반환합니다. 읽기 전용 [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | datetime 필드의 내용을 대체할 날짜와 시간을 반환하거나 설정합니다. 기본값은 이 Presentation 객체가 생성된 시각입니다. 읽기/쓰기 DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | 프레젠테이션의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | 도형에 대한 기본 텍스트 스타일을 반환합니다. 읽기 전용 [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | 프레젠테이션 서명에 사용되는 서명 컬렉션을 반환합니다. 읽기 전용 [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | 표준 및 사용자 정의 문서 속성을 포함하는 DocumentProperties 객체를 반환합니다. 읽기 전용 [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | 프레젠테이션의 첫 슬라이드 번호를 나타냅니다. 읽기/쓰기 Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | 글꼴 관리자를 반환합니다. 읽기 전용 [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | 프레젠테이션의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | 모든 프레젠테이션 슬라이드(마스터, 레이아웃, 노트 슬라이드 제외)에 포함된 모든 하이퍼링크에 쉽게 접근할 수 있습니다. 읽기 전용 [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | 프레젠테이션에 포함된 모든 이미지의 컬렉션을 반환합니다. 읽기 전용 [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | 프레젠테이션에 정의된 모든 레이아웃 슬라이드 목록을 반환합니다. 읽기 전용 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | 핸드아웃 마스터 관리자를 반환합니다. 읽기 전용 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | 노트 마스터 관리자를 반환합니다. 읽기 전용 [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | 프레젠테이션에 정의된 모든 마스터 슬라이드 목록을 반환합니다. 읽기 전용 [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | 프레젠테이션의 마스터 테마를 반환합니다. 읽기 전용 [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | 노트 슬라이드 크기 객체를 반환합니다. 읽기 전용 [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | 이 프레젠테이션에 대한 권한 관리자를 가져옵니다. 읽기 전용 [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | 프레젠테이션에 정의된 모든 슬라이드 섹션 목록을 반환합니다. 읽기 전용 [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | 프레젠테이션 문서에 적용된 민감도 레이블 컬렉션을 반환합니다. 읽기 전용 [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | 프레젠테이션에 정의된 모든 슬라이드 목록을 반환합니다. 읽기 전용 [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | 슬라이드 크기 객체를 반환합니다. 읽기 전용 [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | 프레젠테이션이 로드된 형식에 대한 정보를 반환합니다. 읽기 전용 [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져옵니다. 읽기/쓰기 [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | 프레젠테이션에 포함된 모든 임베디드 비디오 파일 컬렉션을 반환합니다. 읽기 전용 [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | 프레젠테이션 전체 뷰 속성을 가져옵니다. 읽기 전용 [`IViewProperties`](../iviewproperties). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | 프레젠테이션의 지정된 슬라이드에 대한 썸네일 비트맵 객체를 반환합니다. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | 지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | 맞춤 스케일링으로 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 지정된 크기로 지정된 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 맞춤 스케일링으로 지정된 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | ID로 Slide, MasterSlide 또는 LayoutSlide를 반환합니다. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | 정규식과 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | 모든 슬라이드의 모든 허용된 도형에 있는 모든 단락에서 동일한 형식의 런을 결합합니다. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | 정규식과 일치하는 모든 항목을 지정된 문자열로 교체합니다. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | 프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합에 저장합니다. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | 프레젠테이션의 모든 슬라이드를 지정된 형식의 파일에 저장합니다. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | 프레젠테이션의 지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 스트림에 저장합니다. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | 프레젠테이션의 지정된 슬라이드를 지정된 형식의 파일에 저장합니다. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 파일에 저장합니다. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 프레젠테이션의 지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 프레젠테이션의 지정된 슬라이드를 지정된 형식의 파일에 저장합니다. |

### 참조

* 인터페이스 [IPresentationComponent](../ipresentationcomponent)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->