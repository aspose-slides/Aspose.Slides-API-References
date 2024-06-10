---
title: ISlideCollection
second_title: Aspose.Sildes for .NET API Reference
description: Represents a collection of a slides.
type: docs
weight: 6710
url: /aspose.slides/islidecollection/
---

## ISlideCollection interface

Represents a collection of a slides.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Properties

| Name | Description |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Gets the element at the specified index. Read-only [`ISlide`](../islide). |

## Methods

| Name | Description |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Adds a copy of a specified slide to the end of the collection. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Adds a copy of a specified slide to the end of the collection. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Adds a copy of a specified slide to the end of the specified section. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Adds a new empty slide to the end of the collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Creates slides from the PDF document and adds them to the end of the collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Creates slides from the PDF document and adds them to the end of the collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Creates slides from the PDF document and adds them to the end of the collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Returns an index of the specified slide in the collection. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Inserts a copy of a specified slide to specified position of the collection. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Inserts a copy of a specified slide to specified position of the collection. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Inserts a copy of a specified slide to specified position of the collection. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, TextReader) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, string, IExternalResourceResolver, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, TextReader, IExternalResourceResolver, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Removes the first occurrence of a specific object from the collection. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Removes the element at the specified index of the collection. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Moves slide from the collection to the specified position. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Creates and returns an array with all slides in it. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Creates and returns an array with all slides from the specified range in it. |

### See Also

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
