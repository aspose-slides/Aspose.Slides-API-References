---
title: SlideCollection
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 슬라이드 컬렉션을 나타냅니다.
type: docs
weight: 9970
url: /ko/aspose.slides/slidecollection/
---
## SlideCollection 클래스

슬라이드 컬렉션을 나타냅니다.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | 컬렉션에 대한 액세스가 동기화되어 있는지(스레드 안전) 여부를 반환합니다. 읽기 전용 Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | 지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | 동기화 루트를 반환합니다. 읽기 전용 Object. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | 지정된 슬라이드의 사본을 컬렉션 끝에 추가합니다. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 지정된 슬라이드의 사본을 컬렉션 끝에 추가합니다. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | 지정된 섹션의 끝에 지정된 슬라이드 사본을 추가합니다. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 지정된 소스 슬라이드의 사본을 컬렉션 끝에 추가합니다. 적절한 레이아웃이 지정된 마스터에서 자동으로 선택됩니다(적절한 레이아웃은 소스 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃). 적절한 레이아웃이 없으면 소스 슬라이드 레이아웃이 복제됩니다(allowCloneMissingLayout이 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout이 false인 경우). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | 새 빈 슬라이드를 컬렉션 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF 문서에서 슬라이드를 생성하고 pdf 가져오기 옵션을 고려하여 컬렉션 끝에 추가합니다. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | 컬렉션을 순회하는 열거자를 반환합니다. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | 컬렉션에서 지정된 슬라이드의 인덱스를 반환합니다. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | 지정된 위치에 지정된 슬라이드 사본을 삽입합니다. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 지정된 위치에 지정된 슬라이드 사본을 삽입합니다. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 지정된 위치에 지정된 소스 슬라이드의 사본을 삽입합니다. 적절한 레이아웃이 지정된 마스터에서 자동으로 선택됩니다(적절한 레이아웃은 소스 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃). 적절한 레이아웃이 없으면 소스 슬라이드 레이아웃이 복제됩니다(allowCloneMissingLayout이 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout이 false인 경우). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | 지정된 위치에 지정된 슬라이드 사본을 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 삽입합니다. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | 지정된 객체의 첫 번째 발생을 컬렉션에서 제거합니다. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | 지정된 인덱스에 있는 요소를 컬렉션에서 제거합니다. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | 슬라이드를 컬렉션에서 지정된 위치로 이동합니다. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | 슬라이드를 컬렉션에서 지정된 위치로 이동합니다. 슬라이드는 지정된 인덱스부터 리스트에 나타나는 순서대로 배치됩니다. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | 모든 슬라이드를 포함하는 배열을 생성하여 반환합니다. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | 지정된 범위의 슬라이드로 배열을 생성하여 반환합니다. 첫 번째 슬라이드의 인덱스와 추가할 슬라이드 수를 지정합니다. |

### 참조

* 클래스 [DomObject&lt;TParent&gt;](../domobject-1)
* 클래스 [Presentation](../presentation)
* 인터페이스 [ISlideCollection](../islidecollection)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->