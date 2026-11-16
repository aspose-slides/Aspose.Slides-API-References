---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API 참조
description: 프레젠테이션의 속성을 나타냅니다.
type: docs
weight: 5730
url: /ko/aspose.slides/idocumentproperties/
---
## IDocumentProperties 인터페이스

프레젠테이션의 속성을 나타냅니다.

```csharp
public interface IDocumentProperties
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | 응용 프로그램의 템플릿을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | 앱 버전을 반환합니다. 읽기 전용 String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | 프레젠테이션 작성자를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | 프레젠테이션의 카테고리를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | 프레젠테이션의 주석을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | 회사 속성을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | 프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | 프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | 컬렉션에 실제로 포함된 사용자 정의 속성의 수를 반환합니다. 읽기 전용 Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | 프레젠테이션이 생성된 날짜를 반환합니다. 값은 UTC 기준입니다. 읽기/쓰기 DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | 문서 파트의 그룹화와 각 그룹의 파트 수를 나타냅니다. 읽기 전용 IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | 프레젠테이션 문서의 숨겨진 슬라이드 수를 지정합니다. 읽기 전용 Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | HyperlinkBase 문서 속성을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | 한 개 이상의 하이퍼링크가 이 파트에서만 제작자에 의해 업데이트되었음을 지정합니다. 다음 제작자가 이 문서를 열면 해당 파트에 지정된 새로운 하이퍼링크로 하이퍼링크 관계를 업데이트합니다. 읽기/쓰기 Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | 지정된 이름과 연관된 사용자 정의 속성을 반환하거나 설정합니다. 읽기/쓰기 Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | 프레젠테이션의 키워드를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. 읽기/쓰기 DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | 프레젠테이션을 마지막으로 수정한 사람의 이름을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. 값은 UTC 기준입니다. Presentation.DocumentProperties의 경우 읽기 전용입니다(IPresentation 객체 저장 과정에서 내부적으로 업데이트되기 때문). [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 메서드가 반환하는 DocumentProperties 인스턴스를 통해 변경할 수 있습니다. [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) 메서드 요약의 예제를 참조하십시오. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | 문서의 하이퍼링크가 최신인지 여부를 나타냅니다. 하이퍼링크가 업데이트된 것을 나타내려면 이 요소를 **true** 로 설정합니다. 하이퍼링크가 오래된 것을 나타내려면 **false** 로 설정합니다. 읽기/쓰기 Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | 관리자 속성을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | 문서에 포함된 사운드 또는 비디오 클립의 총 수를 지정합니다. 읽기 전용 Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | 응용 프로그램의 이름을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | 노트를 포함하는 프레젠테이션 슬라이드 수를 지정합니다. 읽기 전용 Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | 문서에 포함된 단락의 총 수를 지정합니다(해당되는 경우). 읽기 전용 Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | 프레젠테이션의 의도된 형식을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | 프레젠테이션 개정 번호를 반환하거나 설정합니다. 읽기/쓰기 Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | 문서 썸네일의 표시 모드를 나타냅니다. 썸네일을 디스플레이에 맞게 확대하려면 이 요소를 **true** 로 설정합니다. 썸네일을 디스플레이에 맞는 부분만 표시하도록 자르려면 **false** 로 설정합니다. 읽기/쓰기 Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | 프레젠테이션이 여러 사람과 공유되는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | 프레젠테이션 문서의 총 슬라이드 수를 지정합니다. 읽기 전용 Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | 프레젠테이션의 주제를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | 프레젠테이션의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | 각 문서 파트의 제목을 지정합니다. 이 파트들은 실제 문서 파트가 아니라 문서 섹션을 개념적으로 표현한 것입니다. 읽기 전용 string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | 프레젠테이션의 총 편집 시간을 나타냅니다. 읽기/쓰기 TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | 문서에 포함된 총 단어 수를 지정합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | 모든 내장 속성을 지우고 기본값으로 설정합니다. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | 모든 사용자 정의 속성을 제거합니다. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | 지정된 이름을 가진 사용자 정의 속성의 존재 여부를 확인합니다. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | 지정된 인덱스에 있는 사용자 정의 속성 이름을 반환합니다. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 사용자 정의 속성에서 지정된 이름의 Boolean 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 사용자 정의 속성에서 지정된 이름의 DateTime 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 사용자 정의 속성에서 지정된 이름의 double 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 사용자 정의 속성에서 지정된 이름의 float 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 사용자 정의 속성에서 지정된 이름의 정수 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 사용자 정의 속성에서 지정된 이름의 문자열 값을 가져옵니다. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | 사용자 정의 문서 속성에서 민감도 레이블 배열을 가져옵니다(Microsoft Information Protection SDK 메타데이터). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | 지정된 이름과 연관된 사용자 정의 속성을 제거합니다. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 지정된 이름의 Boolean 사용자 정의 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 지정된 이름의 DateTime 사용자 정의 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 지정된 이름의 double 사용자 정의 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 지정된 이름의 float 사용자 정의 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 지정된 이름의 정수 사용자 정의 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 지정된 이름의 문자열 사용자 정의 속성을 설정합니다. |

### 참조

* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->