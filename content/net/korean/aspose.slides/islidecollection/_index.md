---
title: ISlideCollection
second_title: Aspose.Sildes for .NET API 참조
description: 슬라이드 컬렉션을 나타냅니다.
type: docs
weight: 7050
url: /ko/aspose.slides/islidecollection/
---
## ISlideCollection 인터페이스

슬라이드 컬렉션을 나타냅니다.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## 속성

| Name | Description |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | 지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [`ISlide`](../islide). |

## 메서드

| Name | Description |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | 컬렉션의 끝에 지정된 슬라이드의 복사본을 추가합니다. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 컬렉션의 끝에 지정된 슬라이드의 복사본을 추가합니다. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | 지정된 섹션의 끝에 지정된 슬라이드의 복사본을 추가합니다. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 컬렉션의 끝에 지정된 원본 슬라이드의 복사본을 추가합니다. 적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다(적절한 레이아웃은 원본 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃). 적절한 레이아웃이 없으면 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | 새 빈 슬라이드를 컬렉션의 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | PDF 문서에서 슬라이드를 생성하고 컬렉션의 끝에 추가합니다. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | PDF 문서에서 슬라이드를 생성하고 pdf 가져오기 옵션을 고려하여 컬렉션의 끝에 추가합니다. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | 컬렉션에서 지정된 슬라이드의 인덱스를 반환합니다. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | 컬렉션의 지정된 위치에 지정된 슬라이드의 복사본을 삽입합니다. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 컬렉션의 지정된 위치에 지정된 슬라이드의 복사본을 삽입합니다. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 컬렉션의 지정된 위치에 지정된 원본 슬라이드의 복사본을 삽입합니다. 적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다(적절한 레이아웃은 원본 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃). 적절한 레이아웃이 없으면 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | 컬렉션의 지정된 위치에 지정된 슬라이드의 복사본을 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | HTML 텍스트에서 슬라이드를 생성하고 지정된 위치에 컬렉션에 삽입합니다. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | 컬렉션에서 슬라이드를 지정된 위치로 이동합니다. 슬라이드는 인덱스부터 리스트에 표시된 순서대로 배치됩니다. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | 모든 슬라이드가 포함된 배열을 생성하고 반환합니다. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | 지정된 범위의 모든 슬라이드가 포함된 배열을 생성하고 반환합니다. |

### 참고

* 인터페이스 [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* 인터페이스 [ISlide](../islide)
* 네임스페이스 [Aspose.Slides](../../aspose.slides)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->