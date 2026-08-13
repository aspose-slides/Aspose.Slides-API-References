---
title: IDocumentProperties
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션의 속성을 나타냅니다.
type: docs
weight: 1977
url: /ko/aspose.slides/idocumentproperties/
---
## IDocumentProperties 클래스

프레젠테이션의 속성을 나타냅니다.

```cpp
class IDocumentProperties : public virtual System::Object
```

## 메서드

| Method | 설명 |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | 모든 builtIn 속성에 대한 기본값을 지우고 설정합니다. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | 모든 사용자 정의 속성을 제거합니다. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | 지정된 이름을 가진 사용자 정의 속성의 존재 여부를 확인합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | 응용 프로그램의 템플릿을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | 앱 버전을 반환합니다. 읽기 전용 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | 프레젠테이션의 작성자를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | 프레젠테이션의 카테고리를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | 프레젠테이션의 주석을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | 회사 속성을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | 프레젠테이션의 콘텐츠 상태를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | 프레젠테이션의 콘텐츠 유형을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | 컬렉션에 실제로 포함된 사용자 정의 속성 수를 반환합니다. 읽기 전용 **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | 프레젠테이션이 생성된 날짜를 반환합니다. 값은 UTC 기준입니다. 읽기 [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | 각 문서 부분의 제목을 지정합니다. 이러한 부분은 실제 문서 부분이 아니라 문서 섹션의 개념적 표현입니다. 읽기 전용 [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | 프레젠테이션 문서에서 숨겨진 슬라이드 수를 지정합니다. 읽기 전용 **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | HyperlinkBase 문서 속성을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | 이 부분의 하나 이상의 하이퍼링크가 생산자에 의해 이 부분에서만 업데이트되었음을 지정합니다. 다음 생산자가 문서를 열 때 이 부분에 지정된 새 하이퍼링크와 함께 하이퍼링크 관계를 업데이트해야 합니다. 읽기 **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | 프레젠테이션의 키워드를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. 읽기 [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | 프레젠테이션을 마지막으로 수정한 사람의 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. 값은 UTC 기준입니다. Presentation.DocumentProperties의 경우 읽기 전용입니다([IPresentation](../ipresentation/) 객체 저장 과정에서 내부적으로 업데이트되기 때문). [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 메서드가 반환하는 [DocumentProperties](../documentproperties/) 인스턴스를 통해 변경할 수 있습니다. 자세한 예시는 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 메서드 요약을 참조하십시오. |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | 문서의 하이퍼링크가 최신인지 여부를 나타냅니다. 하이퍼링크가 업데이트되었음을 나타내려면 이 요소를 **true** 로 설정하십시오. 하이퍼링크가 오래되었음을 나타내려면 이 요소를 **false** 로 설정하십시오. 읽기 **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | 관리자 속성을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | 문서에 포함된 사운드 또는 비디오 클립의 총 수를 지정합니다. 읽기 전용 **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | 응용 프로그램의 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | 노트를 포함한 프레젠테이션 슬라이드 수를 지정합니다. 읽기 전용 **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | 해당되는 경우 문서에서 찾은 전체 문단 수를 지정합니다. 읽기 전용 **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | 프레젠테이션의 의도된 형식을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | 프레젠테이션 리비전 번호를 반환합니다. 읽기 **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | 문서 썸네일의 표시 모드를 나타냅니다. 썸네일을 디스플레이에 맞게 확대하려면 이 요소를 **true** 로 설정하십시오. 디스플레이에 맞게 섹션만 표시하도록 썸네일을 자르려면 이 요소를 **false** 로 설정하십시오. 읽기 **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | 프레젠테이션이 여러 사람과 공유되는지 여부를 결정합니다. 읽기 **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | 프레젠테이션 문서의 총 슬라이드 수를 지정합니다. 읽기 전용 **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | 프레젠테이션의 주제를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | 프레젠테이션의 제목을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | 각 문서 부분의 제목을 지정합니다. 이러한 부분은 실제 문서 부분이 아니라 문서 섹션의 개념적 표현입니다. 읽기 전용 [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | 프레젠테이션의 총 편집 시간입니다. 읽기 [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | 문서에 포함된 전체 단어 수를 지정합니다. 읽기 전용 **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | 지정된 인덱스의 사용자 정의 속성 이름을 반환합니다. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | 사용자 정의 속성에서 지정된 이름의 부울 값을 가져옵니다. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | 사용자 정의 속성에서 지정된 이름의 정수 값을 가져옵니다. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | 사용자 정의 속성에서 지정된 이름의 DateTime 값을 가져옵니다. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | 사용자 정의 속성에서 지정된 이름의 문자열 값을 가져옵니다. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | 사용자 정의 속성에서 지정된 이름의 float 값을 가져옵니다. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | 사용자 정의 속성에서 지정된 이름의 double 값을 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | 맞춤 문서 속성에서 민감도 레이블 배열을 가져옵니다 (Microsoft Information Protection SDK 메타데이터). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | 지정된 이름과 연결된 사용자 정의 속성을 반환합니다. 읽기 [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 지정된 이름과 연결된 사용자 정의 속성을 설정합니다. 쓰기 [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# ‘is’ 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 유형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | 지정된 이름과 연결된 사용자 정의 속성을 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | 응용 프로그램의 템플릿을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | 프레젠테이션의 작성자를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | 프레젠테이션의 카테고리를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | 프레젠테이션의 주석을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | 회사 속성을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | 프레젠테이션의 콘텐츠 상태를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | 프레젠테이션의 콘텐츠 유형을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | 프레젠테이션이 생성된 날짜를 반환합니다. 값은 UTC 기준입니다. 쓰기 [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | HyperlinkBase 문서 속성을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | 이 부분의 하나 이상의 하이퍼링크가 생산자에 의해 이 부분에서만 업데이트되었음을 지정합니다. 다음 생산자가 문서를 열 때 이 부분에 지정된 새 하이퍼링크와 함께 하이퍼링크 관계를 업데이트해야 합니다. 쓰기 **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | 프레젠테이션의 키워드를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. 쓰기 [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | 프레젠테이션을 마지막으로 수정한 사람의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. 값은 UTC 기준입니다. Presentation.DocumentProperties의 경우 읽기 전용입니다([IPresentation](../ipresentation/) 객체 저장 과정에서 내부적으로 업데이트되기 때문). [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 메서드가 반환하는 [DocumentProperties](../documentproperties/) 인스턴스를 통해 변경할 수 있습니다. 자세한 예시는 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 메서드 요약을 참조하십시오. |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | 문서의 하이퍼링크가 최신인지 여부를 나타냅니다. 하이퍼링크가 업데이트되었음을 나타내려면 이 요소를 **true** 로 설정하십시오. 하이퍼링크가 오래되었음을 나타내려면 이 요소를 **false** 로 설정하십시오. 쓰기 **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | 관리자 속성을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | 응용 프로그램의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | 프레젠테이션의 의도된 형식을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | 프레젠테이션 리비전 번호를 설정합니다. 쓰기 **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | 문서 썸네일의 표시 모드를 나타냅니다. 썸네일을 디스플레이에 맞게 확대하려면 이 요소를 **true** 로 설정하십시오. 디스플레이에 맞게 섹션만 표시하도록 썸네일을 자르려면 이 요소를 **false** 로 설정하십시오. 쓰기 **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | 프레젠테이션이 여러 사람과 공유되는지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | 프레젠테이션의 주제를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | 프레젠테이션의 제목을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | 프레젠테이션의 총 편집 시간입니다. 쓰기 [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | 지정된 이름의 부울 사용자 정의 속성을 설정합니다. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | 지정된 이름의 정수 사용자 정의 속성을 설정합니다. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | 지정된 이름의 DateTime 사용자 정의 속성을 설정합니다. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | 지정된 이름의 문자열 사용자 정의 속성을 설정합니다. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | 지정된 이름의 float 사용자 정의 속성을 설정합니다. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | 지정된 이름의 double 사용자 정의 속성을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 강한 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)