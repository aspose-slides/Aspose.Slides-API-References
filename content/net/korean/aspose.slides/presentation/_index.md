---
title: Presentation
second_title: Aspose.Sildes용 .NET API 레퍼런스
description: Microsoft PowerPoint 프레젠테이션을 나타냅니다.
type: docs
weight: 9590
url: /ko/aspose.slides/presentation/
---
## Presentation 클래스

Microsoft PowerPoint 프레젠테이션을 나타냅니다.

```csharp
public sealed class Presentation : IPresentation
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Presentation](presentation#constructor)() | 이 생성자는 새 프레젠테이션을 처음부터 만듭니다. 만든 프레젠테이션은 비어 있는 슬라이드 하나를 포함합니다. |
| [Presentation](presentation#constructor_1)(LoadOptions) | 이 생성자는 새 프레젠테이션을 처음부터 만듭니다. 만든 프레젠테이션은 비어 있는 슬라이드 하나를 포함합니다. |
| [Presentation](presentation#constructor_2)(Stream) | 이 생성자는 기존 프레젠테이션을 읽는 주요 메커니즘입니다. |
| [Presentation](presentation#constructor_4)(string) | 이 생성자는 프레젠테이션 내용이 읽히는 소스 파일 경로를 가져옵니다. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | 이 생성자는 기존 프레젠테이션을 읽는 주요 메커니즘입니다. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | 이 생성자는 프레젠테이션 내용이 읽히는 소스 파일 경로를 가져옵니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | 프레젠테이션의 모든 사용자 정의 데이터 파트를 반환합니다. 읽기 전용 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | 프레젠테이션에 포함된 모든 임베디드 오디오 파일 컬렉션을 반환합니다. 읽기 전용 [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | 댓글 작성자 컬렉션을 반환합니다. 읽기 전용 [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | datetime 필드의 내용을 대체할 날짜와 시간을 반환하거나 설정합니다. 기본값은 이 Presentation 객체가 생성된 시간입니다. 읽기/쓰기 DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | 프레젠테이션의 사용자 정의 데이터를 반환합니다. 읽기 전용 [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | 모양에 대한 기본 텍스트 스타일을 반환합니다. 읽기 전용 [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | 프레젠테이션 서명에 사용된 서명 컬렉션을 반환합니다. 읽기 전용 [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | 표준 및 사용자 정의 문서 속성을 포함하는 DocumentProperties 객체를 반환합니다. 읽기 전용 [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | 프레젠테이션에서 첫 슬라이드 번호를 나타냅니다. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | 폰트 관리자를 반환합니다. 읽기 전용 [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | 실제 HeaderFooter 관리자를 반환합니다. 읽기 전용 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | 모든 프레젠테이션 슬라이드(마스터, 레이아웃, 노트 슬라이드 제외)에 포함된 모든 하이퍼링크에 쉽게 접근할 수 있도록 합니다. 읽기 전용 [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | 프레젠테이션에 포함된 모든 이미지 컬렉션을 반환합니다. 읽기 전용 [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | 프레젠테이션에 정의된 모든 레이아웃 슬라이드 목록을 반환합니다. 읽기 전용 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | 핸드아웃 마스터 관리자를 반환합니다. 읽기 전용 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | 노트 마스터 관리자를 반환합니다. 읽기 전용 [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | 프레젠테이션에 정의된 모든 마스터 슬라이드 목록을 반환합니다. 읽기 전용 [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | 마스터 테마를 반환합니다. 읽기 전용 [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | 노트 슬라이드 크기 객체를 반환합니다. 읽기 전용 [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | 이 프레젠테이션에 대한 권한 관리자를 가져옵니다. 읽기 전용 [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | 프레젠테이션에 정의된 모든 슬라이드 섹션 목록을 반환합니다. 읽기 전용 [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | 프레젠테이션 문서에 적용된 민감도 라벨 컬렉션을 반환합니다. 읽기 전용 [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | 프레젠테이션에 정의된 모든 슬라이드 목록을 반환합니다. 읽기 전용 [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | 프레젠테이션의 슬라이드 쇼 설정을 반환합니다. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | 슬라이드 크기 객체를 반환합니다. 읽기 전용 [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | 프레젠테이션이 로드된 형식에 대한 정보를 반환합니다. 읽기 전용 [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져오거나 설정합니다. 읽기/쓰기 [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | 프레젠테이션에 포함된 모든 임베디드 비디오 파일 컬렉션을 반환합니다. 읽기 전용 [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | 프레젠테이션 전체 뷰 속성을 가져옵니다. 읽기 전용 [`IViewProperties`](../iviewproperties). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | 이 Presentation 객체가 사용한 모든 리소스를 해제합니다. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | 프레젠테이션의 모든 슬라이드에 대한 Image 객체를 반환합니다. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | 지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | 사용자 지정 스케일링으로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 지정된 크기로 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 사용자 지정 스케일링으로 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Id에 의해 Slide, MasterSlide 또는 LayoutSlide를 반환합니다. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | 정규식과 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조합니다. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | 모든 슬라이드의 모든 허용 가능한 모양에 있는 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | 정규식과 일치하는 모든 항목을 지정된 문자열로 교체합니다. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | 프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합으로 저장합니다. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장합니다. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | 프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장합니다. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식으로 스트림에 저장합니다. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 스트림에 저장합니다. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식으로 파일에 저장합니다. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식 및 추가 옵션으로 스트림에 저장합니다. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식 및 추가 옵션으로 파일에 저장합니다. |

### 예제

다음 예제는 PowerPoint Presentation을 만드는 방법을 보여줍니다.

```csharp
[C#]
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
using (Presentation presentation = new Presentation())
{
    // 첫 번째 슬라이드를 가져옵니다
    ISlide slide = presentation.Slides[0];
    // 라인 유형의 자동 도형을 추가합니다
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// 프레젠테이션 파일을 저장합니다.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

다음 예제는 Presentation을 열고 저장하는 방법을 보여줍니다.

```csharp
[C#]
// Presentation에서 지원되는 모든 파일을 로드합니다 (예: ppt, pptx, odp 등).
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// 프레젠테이션 파일을 저장합니다.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### 참고

* 인터페이스 [IPresentation](../ipresentation)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->