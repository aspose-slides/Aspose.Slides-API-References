---
title: DocumentProperties
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 프레젠테이션의 속성을 나타냅니다.
type: docs
weight: 2810
url: /ko/aspose.slides/documentproperties/
---
## DocumentProperties 클래스

프레젠테이션의 속성을 나타냅니다.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DocumentProperties](documentproperties)() | 클래스 [`DocumentProperties`](../documentproperties)의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | 응용 프로그램의 템플릿을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | 앱 버전을 반환합니다. 읽기 전용 String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | 프레젠테이션의 작성자를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | 프레젠테이션의 카테고리를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | 프레젠테이션의 댓글을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | 회사 속성을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | 프레젠테이션의 콘텐츠 상태를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | 프레젠테이션의 콘텐츠 유형을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | 컬렉션에 실제 포함된 사용자 지정 속성의 개수를 반환합니다. 읽기 전용 Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | 프레젠테이션이 생성된 날짜를 반환합니다. 값은 UTC 기준입니다. 읽기/쓰기 DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | 문서 파트의 그룹화 및 각 그룹의 파트 수를 나타냅니다. 읽기 전용 IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | 프레젠테이션 문서에서 숨겨진 슬라이드 수를 반환합니다. 읽기 전용 Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | HyperlinkBase 문서 속성을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | 생산자가 이 파트에서 하나 이상의 하이퍼링크를 독점적으로 업데이트했음을 지정합니다. 다음 생산자가 이 문서를 열 때 이 파트에서 지정된 새 하이퍼링크로 하이퍼링크 관계를 업데이트해야 합니다. 읽기/쓰기 Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | 지정된 이름과 연결된 사용자 지정 속성을 반환하거나 설정합니다. 읽기/쓰기 Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | 프레젠테이션의 키워드를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | 프레젠테이션이 마지막으로 인쇄된 날짜를 반환합니다. 읽기/쓰기 DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | 프레젠테이션을 마지막으로 수정한 사람의 이름을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | 프레젠테이션이 마지막으로 수정된 날짜를 반환합니다. 값은 UTC 기준입니다. Presentation.DocumentProperties의 경우(내부적으로 IPresentation 객체 저장 프로세스 중에 업데이트되기 때문에) 읽기 전용입니다. [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) 메서드가 반환하는 DocumentProperties 인스턴스를 통해 변경할 수 있습니다. [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) 메서드 요약의 예제를 참조하십시오. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | 문서의 하이퍼링크가 최신인지 여부를 나타냅니다. 하이퍼링크가 업데이트되었음을 표시하려면 이 요소를 **true**로 설정합니다. 하이퍼링크가 오래되었음을 표시하려면 **false**로 설정합니다. 읽기/쓰기 Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | 관리자 속성을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | 문서에 존재하는 사운드 또는 비디오 클립의 총 개수를 반환합니다. 읽기 전용 Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | 응용 프로그램의 이름을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | 노트를 포함하는 프레젠테이션 슬라이드 수를 반환합니다. 읽기 전용 Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | 해당되는 경우 문서에서 찾은 전체 단락 수를 반환합니다. 읽기 전용 Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | 프레젠테이션의 의도된 형식을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | 프레젠테이션 개정 번호를 반환하거나 설정합니다. 읽기/쓰기 Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | 문서 썸네일의 표시 모드를 나타냅니다. 썸네일을 디스플레이에 맞게 확대하도록 하려면 이 요소를 **true**로 설정합니다. 디스플레이에 맞는 섹션만 표시하도록 썸네일을 잘라내려면 **false**로 설정합니다. 읽기/쓰기 Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | 프레젠테이션이 여러 사람과 공유되는지 여부를 결정합니다. 읽기/쓰기 Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | 프레젠테이션 문서의 총 슬라이드 수를 반환합니다. 읽기 전용 Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | 프레젠테이션의 주제를 반환하거나 설정합니다. 읽기/쓰기 String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | 프레젠테이션의 제목을 반환하거나 설정합니다. 읽기/쓰기 String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | 각 문서 파트의 제목을 지정합니다. 이러한 파트는 실제 문서 파트가 아니라 문서 섹션의 개념적 표현입니다. 읽기 전용 string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | 프레젠테이션의 총 편집 시간입니다. 읽기/쓰기 TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | 문서에 포함된 전체 단어 수를 반환합니다. 읽기 전용 Int32. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | 모든 내장 속성을 지우고 기본값으로 설정합니다. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | 모든 사용자 지정 속성을 제거합니다. |
| [Clone](../../aspose.slides/documentproperties/clone)() | 현재 객체를 복제합니다. |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | 현재 객체를 복제합니다. |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | 지정된 이름을 가진 사용자 지정 속성의 존재 여부를 확인합니다. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | 지정된 인덱스 위치의 사용자 지정 속성 이름을 반환합니다. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | 사용자 지정 속성에서 지정된 이름의 bool 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | 사용자 지정 속성에서 지정된 이름의 DateTime 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | 사용자 지정 속성에서 지정된 이름의 double 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | 사용자 지정 속성에서 지정된 이름의 float 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | 사용자 지정 속성에서 지정된 이름의 정수 값을 가져옵니다. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | 사용자 지정 속성에서 지정된 이름의 문자열 값을 가져옵니다. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | 사용자 지정 문서 속성(Microsoft Information Protection SDK 메타데이터)에서 민감도 레이블 배열을 가져옵니다. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | 지정된 이름과 연결된 사용자 지정 속성을 제거합니다. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | 지정된 이름의 bool 사용자 지정 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | 지정된 이름의 DateTime 사용자 지정 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | 지정된 이름의 double 사용자 지정 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | 지정된 이름의 float 사용자 지정 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | 지정된 이름의 정수 사용자 지정 속성을 설정합니다. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | 지정된 이름의 문자열 사용자 지정 속성을 설정합니다. |

### 예제

다음 예제는 PowerPoint 프레젠테이션의 내장 속성에 액세스하는 방법을 보여줍니다.

```csharp
[C#]
// 프레젠테이션을 나타내는 Presentation 클래스를 인스턴스화합니다
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Presentation와 연결된 IDocumentProperties 객체에 대한 참조를 생성합니다
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// 내장 속성을 표시합니다
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

다음 예제는 PowerPoint 프레젠테이션의 내장 속성을 수정하는 방법을 보여줍니다.

```csharp
[C#]
// 프레젠테이션을 나타내는 Presentation 클래스를 인스턴스화합니다
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Presentation와 연결된 IDocumentProperties 객체에 대한 참조를 생성합니다
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// 내장 속성을 설정합니다
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// 프레젠테이션을 파일에 저장합니다
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### 참조

* 인터페이스 [IDocumentProperties](../idocumentproperties)
* 인터페이스 [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->