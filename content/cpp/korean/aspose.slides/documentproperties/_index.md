---
title: DocumentProperties
second_title: C++용 Aspose.Slides API 레퍼런스
description: 프레젠테이션의 속성을 나타냅니다.
type: docs
weight: 794
url: /ko/aspose.slides/documentproperties/
---
## DocumentProperties 클래스

프레젠테이션의 속성을 나타냅니다.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## 메서드

| Method | Description |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | 모든 builtIn 속성을 지우고 기본값으로 설정합니다. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | 모든 사용자 정의 속성을 제거합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | 현재 객체를 복제합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | 현재 객체를 복제합니다. |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | 지정된 이름을 가진 사용자 정의 속성의 존재를 확인합니다. |
|  [DocumentProperties](./documentproperties/)() | [DocumentProperties](./) 클래스의 새 인스턴스를 초기화합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | 응용 프로그램의 템플릿을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | 앱 버전을 반환합니다. 읽기 전용 [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | 프레젠테이션의 저자를 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | 프레젠테이션의 카테고리를 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | 프레젠테이션의 주석을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | 회사 속성을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | 프레젠테이션의 콘텐츠 상태를 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | 프레젠테이션의 콘텐츠 유형을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | 컬렉션에 실제로 포함된 사용자 정의 속성의 수를 반환합니다. 읽기 전용 **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | 프레젠테이션이 생성된 날짜를 반환합니다. 값은 UTC 기준입니다. [System::DateTime](../../system/datetime/)을(를) 읽으세요. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | 문서 파트의 그룹화 및 각 그룹의 파트 수를 나타냅니다. 읽기 전용 [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | 프레젠테이션 문서에서 숨겨진 슬라이드 수를 반환합니다. 읽기 전용 **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | HyperlinkBase 문서 속성을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | 이 파트의 하나 이상의 하이퍼링크가 해당 파트에서만 제작자에 의해 업데이트되었음을 지정합니다. 다음 제작자가 이 문서를 열면 이 파트에 지정된 새 하이퍼링크로 하이퍼링크 관계를 업데이트해야 합니다. 읽기 **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | 프레젠테이션의 키워드를 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. [System::DateTime](../../system/datetime/)을(를) 읽으세요. |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | 프레젠테이션을 마지막으로 수정한 사람의 이름을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. 값은 UTC 기준입니다. [Presentation::get_DocumentProperties](../presentation/get_documentproperties/)인 경우 읽기 전용입니다([IPresentation](../ipresentation/) 객체 저장 과정에서 내부적으로 업데이트되기 때문). [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 메서드가 반환하는 [DocumentProperties](./) 인스턴스를 통해 변경할 수 있습니다. 자세한 예는 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 메서드 요약을 참조하십시오. |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | 문서의 하이퍼링크가 최신 상태인지 표시합니다. 하이퍼링크가 업데이트되었음을 나타내려면 이 요소를 **true**로 설정하고, 오래됐음을 나타내려면 **false**로 설정합니다. 읽기 **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | 관리자 속성을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | 문서에 포함된 사운드 또는 비디오 클립의 총 수를 반환합니다. 읽기 전용 **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | 응용 프로그램의 이름을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| **int32_t** [get_Notes](./get_notes/)() override | 노트가 포함된 프레젠테이션 슬라이드 수를 반환합니다. 읽기 전용 **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | 문서에서 발견된 단락의 총 수를 반환합니다(해당되는 경우). 읽기 전용 **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | 프레젠테이션의 의도된 형식을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | 프레젠테이션 리비전 번호를 반환합니다. 읽기 **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | 문서 썸네일의 표시 모드를 나타냅니다. 썸네일을 디스플레이에 맞게 확대하려면 **true**로, 디스플레이에 맞는 섹션만 보이도록 자르려면 **false**로 설정합니다. 읽기 **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | 프레젠테이션이 여러 사람과 공유되는지 여부를 결정합니다. 읽기 **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | 프레젠테이션 문서의 전체 슬라이드 수를 반환합니다. 읽기 전용 **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | 프레젠테이션의 주제를 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | 프레젠테이션의 제목을 반환합니다. [System::String](../../system/string/)을(를) 읽으세요. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | 각 문서 파트의 제목을 지정합니다. 이 파트들은 실제 문서 파트가 아니라 문서 섹션의 개념적 표현입니다. 읽기 전용 [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | 프레젠테이션의 전체 편집 시간입니다. [System::TimeSpan](../../system/timespan/)을(를) 읽으세요. |
| **int32_t** [get_Words](./get_words/)() override | 문서에 포함된 전체 단어 수를 반환합니다. 읽기 전용 **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | 지정된 인덱스에 있는 사용자 정의 속성 이름을 반환합니다. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | 사용자 정의 속성에서 지정된 이름의 부울 값을 가져옵니다. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | 사용자 정의 속성에서 지정된 이름의 정수 값을 가져옵니다. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | 사용자 정의 속성에서 지정된 이름의 DateTime 값을 가져옵니다. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | 사용자 정의 속성에서 지정된 이름의 문자열 값을 가져옵니다. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | 사용자 정의 속성에서 지정된 이름의 float 값을 가져옵니다. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | 사용자 정의 속성에서 지정된 이름의 double 값을 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | 사용자 정의 문서 속성(Microsoft Information Protection SDK 메타데이터)에서 민감도 라벨 배열을 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | 지정된 이름과 연결된 사용자 정의 속성을 반환합니다. [System::Object](../../system/object/)을(를) 읽으세요. |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 이름과 연결된 사용자 정의 속성을 설정합니다. [System::Object](../../system/object/)을(를) 씁니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장에 대한 잠금 구현입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 기준으로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | 지정된 이름과 연결된 사용자 정의 속성을 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | 응용 프로그램의 템플릿을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | 프레젠테이션의 저자를 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | 프레젠테이션의 카테고리를 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | 프레젠테이션의 주석을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | 회사 속성을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | 프레젠테이션의 콘텐츠 상태를 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | 프레젠테이션의 콘텐츠 유형을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | 프레젠테이션이 생성된 날짜를 반환합니다. 값은 UTC 기준입니다. [System::DateTime](../../system/datetime/)을(를) 씁니다. |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | HyperlinkBase 문서 속성을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | 이 파트의 하나 이상의 하이퍼링크가 해당 파트에서만 제작자에 의해 업데이트되었음을 지정합니다. 다음 제작자가 이 문서를 열면 이 파트에 지정된 새 하이퍼링크로 하이퍼링크 관계를 업데이트해야 합니다. **bool**을(를) 씁니다. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | 프레젠테이션의 키워드를 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. [System::DateTime](../../system/datetime/)을(를) 씁니다. |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | 프레젠테이션을 마지막으로 수정한 사람의 이름을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. 값은 UTC 기준입니다. [Presentation::get_DocumentProperties](../presentation/get_documentproperties/)인 경우 읽기 전용입니다([IPresentation](../ipresentation/) 객체 저장 과정에서 내부적으로 업데이트되기 때문). [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) 메서드가 반환하는 [DocumentProperties](./) 인스턴스를 통해 변경할 수 있습니다. 자세한 예는 [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) 메서드 요약을 참조하십시오. |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | 문서의 하이퍼링크가 최신 상태인지 표시합니다. 하이퍼링크가 업데이트되었음을 나타내려면 **true**로, 오래됐음을 나타내려면 **false**로 설정합니다. **bool**을(를) 씁니다. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | 관리자 속성을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | 응용 프로그램 이름을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | 프레젠테이션의 의도된 형식을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | 프레젠테이션 리비전 번호를 설정합니다. **int32_t**을(를) 씁니다. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | 문서 썸네일의 표시 모드를 나타냅니다. 썸네일을 디스플레이에 맞게 확대하려면 **true**로, 디스플레이에 맞는 섹션만 보이도록 자르려면 **false**로 설정합니다. **bool**을(를) 씁니다. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | 프레젠테이션이 여러 사람과 공유되는지 여부를 결정합니다. **bool**을(를) 씁니다. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | 프레젠테이션의 주제를 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | 프레젠테이션의 제목을 설정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | 프레젠테이션의 전체 편집 시간입니다. [System::TimeSpan](../../system/timespan/)을(를) 씁니다. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | 지정된 이름의 부울 사용자 정의 속성을 설정합니다. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | 지정된 이름의 정수 사용자 정의 속성을 설정합니다. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | 지정된 이름의 DateTime 사용자 정의 속성을 설정합니다. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | 지정된 이름의 문자열 사용자 정의 속성을 설정합니다. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | 지정된 이름의 float 사용자 정의 속성을 설정합니다. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | 지정된 이름의 double 사용자 정의 속성을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장에 대한 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

다음 예제는 PowerPoint [Presentation](../presentation/)의 내장 속성에 액세스하는 방법을 보여줍니다.
```cpp
// 프레젠테이션을 나타내는 Presentation 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
다음 예제는 PowerPoint [Presentation](../presentation/)의 내장 속성을 수정하는 방법을 보여줍니다.
```cpp
// Presentation을 나타내는 Presentation 클래스를 인스턴스화합니다
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Presentation와 연관된 IDocumentProperties 객체에 대한 참조를 생성합니다
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// 내장 속성을 설정합니다
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// 프레젠테이션을 파일에 저장합니다
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [IDocumentProperties](../idocumentproperties/)
* 클래스 [IGenericCloneable](../igenericcloneable/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)