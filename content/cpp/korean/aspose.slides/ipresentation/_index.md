---
title: IPresentation
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션 문서
type: docs
weight: 3368
url: /ko/aspose.slides/ipresentation/
---
## IPresentation 클래스

[Presentation](../presentation/) 문서

```cpp
class IPresentation : public Aspose::Slides::IPresentationComponent,
                      public System::IDisposable
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual void [Dispose](../../system/idisposable/dispose/)() | 아무것도 하지 않습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일의 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일의 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() | 프레젠테이션의 모든 사용자 정의 데이터 부분을 반환합니다. 읽기 전용 [ICustomXmlPart](../icustomxmlpart/)[]. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) | 지정된 인덱스에 있는 프레젠테이션의 내장 오디오 파일을 반환합니다. 읽기 전용 [Aspose::Slides::IAudio](../iaudio/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() | 프레젠테이션에 포함된 모든 오디오 파일 컬렉션을 반환합니다. 읽기 전용 [IAudioCollection](../iaudiocollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) | 지정된 인덱스에 있는 댓글 작성자를 반환합니다. 읽기 전용 [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() | 댓글 작성자 컬렉션을 반환합니다. 읽기 전용 [ICommentAuthorCollection](../icommentauthorcollection/). |
| virtual [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() | datetime 필드의 내용을 대체할 날짜와 시간을 반환합니다. 기본적으로 이 [Presentation](../presentation/) 객체가 생성된 시각을 사용합니다. 읽기 [System::DateTime](../../system/datetime/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | 프레젠테이션의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() | 모양에 대한 기본 텍스트 스타일을 반환합니다. 읽기 전용 [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) | 지정된 인덱스에 있는 프레젠테이션 서명에 사용된 디지털 서명을 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() | 프레젠테이션 서명에 사용된 서명 컬렉션을 반환합니다. 읽기 전용 [IDigitalSignatureCollection](../idigitalsignaturecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() | [DocumentProperties](../documentproperties/) 객체를 반환합니다. 이 객체에는 표준 및 사용자 정의 문서 속성이 포함됩니다. 읽기 전용 [IDocumentProperties](../idocumentproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) | 이름으로 정의된 사용자 정의 속성을 반환합니다. |
| virtual **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() | 프레젠테이션에서 첫 번째 슬라이드 번호를 나타냅니다. 읽기 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() | 폰트 관리자를 반환합니다. 읽기 전용 [IFontsManager](../ifontsmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | 프레젠테이션의 머리글/바닥글 관리자를 반환합니다. 읽기 전용 [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() | 모든 프레젠테이션 슬라이드에 포함된 모든 하이퍼링크에 쉽게 접근할 수 있습니다(마스터, 레이아웃, 노트 슬라이드 제외). 읽기 전용 [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) | 지정된 인덱스에 있는 프레젠테이션의 이미지를 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() | 프레젠테이션에 포함된 모든 이미지 컬렉션을 반환합니다. 읽기 전용 [IImageCollection](../iimagecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | 인덱스로 레이아웃 슬라이드를 반환합니다. 읽기 전용 [Aspose::Slides::ILayoutSlide](../ilayoutslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | 프레젠테이션에 정의된 모든 레이아웃 슬라이드 목록을 반환합니다. 읽기 전용 [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) | 지정된 인덱스에 있는 프레젠테이션의 마스터 슬라이드를 반환합니다. 읽기 전용 [Aspose::Slides::IMasterSlide](../imasterslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() | 핸드아웃 마스터 관리자를 반환합니다. 읽기 전용 [IMasterHandoutSlideManager](../imasterhandoutslidemanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() | 노트 마스터 관리자를 반환합니다. 읽기 전용 [IMasterNotesSlideManager](../imasternotesslidemanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() | 프레젠테이션에 정의된 모든 마스터 슬라이드 목록을 반환합니다. 읽기 전용 [IMasterSlideCollection](../imasterslidecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() | 프레젠테이션의 마스터 테마를 반환합니다. 읽기 전용 [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() | 노트 슬라이드 크기 객체를 반환합니다. 읽기 전용 [INotesSize](../inotessize/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](./)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() | 이 프레젠테이션에 대한 권한 관리자를 가져옵니다. 읽기 전용 [IProtectionManager](../iprotectionmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) | 지정된 인덱스에 정의된 프레젠테이션의 슬라이드 섹션을 반환합니다. 읽기 전용 [Aspose::Slides::ISection](../isection/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() | 프레젠테이션에 정의된 모든 슬라이드 섹션 목록을 반환합니다. 읽기 전용 [ISectionCollection](../isectioncollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() | 프레젠테이션 문서에 적용된 민감도 레이블 컬렉션을 반환합니다. 읽기 전용 [ISensitivityLabelCollection](../isensitivitylabelcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) | 지정된 인덱스에 정의된 프레젠테이션 슬라이드를 반환합니다. 읽기 전용 [Aspose::Slides::ISlide](../islide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() | 프레젠테이션에 정의된 모든 슬라이드 목록을 반환합니다. 읽기 전용 [ISlideCollection](../islidecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() | 슬라이드 크기 객체를 반환합니다. 읽기 전용 [ISlideSize](../islidesize/). |
| virtual [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() | 프레젠테이션이 로드된 형식에 대한 정보를 반환합니다. 읽기 전용 [IPresentation::get_SourceFormat](./get_sourceformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져옵니다. 읽기 [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) | 지정된 인덱스에 있는 프레젠테이션의 내장 비디오 파일을 반환합니다. 읽기 전용 [Aspose::Slides::IVideo](../ivideo/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() | 프레젠테이션에 포함된 모든 내장 비디오 파일 컬렉션을 반환합니다. 읽기 전용 [IVideoCollection](../ivideocollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() | 프레젠테이션 전반에 걸친 보기 속성을 가져옵니다. 읽기 전용 [IViewProperties](../iviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | 프레젠테이션의 지정된 슬라이드에 대한 썸네일 비트맵 객체를 반환합니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) | 사용자 정의 스케일링을 적용한 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) | 사용자 정의 스케일링을 적용한 프레젠테이션의 지정된 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) | 지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) | 지정된 크기로 프레젠테이션의 지정된 슬라이드에 대한 썸네일 이미지 객체를 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) | Id로 [Slide](../slide/), [MasterSlide](../masterslide/) 또는 [LayoutSlide](../layoutslide/)을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 정규 표현식의 모든 일치를 지정된 색으로 강조 표시합니다. |
| virtual void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) | 샘플 텍스트의 모든 일치를 지정된 색으로 강조 표시합니다. |
| virtual void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 샘플 텍스트의 모든 일치를 지정된 색으로 강조 표시합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() | 모든 슬라이드의 모든 허용 가능한 형태에 있는 모든 문단에서 동일한 형식의 실행을 결합합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 정규 표현식의 모든 일치를 지정된 문자열로 교체합니다. |
| virtual void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| virtual void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | 프레젠테이션의 모든 슬라이드를 지정된 형식의 파일에 저장합니다. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | 프레젠테이션의 모든 슬라이드를 지정된 형식의 스트림에 저장합니다. |
| virtual void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 파일에 저장합니다. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | 프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션으로 스트림에 저장합니다. |
| virtual void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | 프레젠테이션의 지정된 슬라이드를 지정된 형식의 파일에 저장합니다. |
| virtual void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | 프레젠테이션의 지정된 슬라이드를 지정된 형식의 파일에 저장합니다. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | 프레젠테이션의 지정된 슬라이드를 지정된 형식의 스트림에 저장합니다. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | 프레젠테이션의 지정된 슬라이드를 지정된 형식의 스트림에 저장합니다. |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) | 프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합에 저장합니다. |
| virtual void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) | datetime 필드의 내용을 대체할 날짜와 시간을 설정합니다. 기본적으로 이 [Presentation](../presentation/) 객체가 생성된 시각을 사용합니다. 쓰기 [System::DateTime](../../system/datetime/). |
| virtual void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 이름으로 정의된 사용자 정의 속성을 설정합니다. |
| virtual void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) | 프레젠테이션의 첫 번째 슬라이드 번호를 나타냅니다. 쓰기 **int32_t**. |
| virtual void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) | 프레젠테이션 매크로가 포함된 VBA 프로젝트를 가져옵니다. 쓰기 [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IPresentationComponent](../ipresentationcomponent/)
* 클래스 [IDisposable](../../system/idisposable/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)