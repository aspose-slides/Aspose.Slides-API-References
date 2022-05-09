---
title: ISlideCollection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 6470
url: /net/aspose.slides/islidecollection/
---
## ISlideCollection interface

Represents a collection of a slides.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Properties

| Name | Description |
| --- | --- |
| [Item](item) { get; } | Gets the element at the specified index. Read-only [`ISlide`](../islide). |

## Methods

| Name | Description |
| --- | --- |
| [AddClone](addclone)(ISlide) | Adds a copy of a specified slide to the end of the collection. |
| [AddClone](addclone)(ISlide, ILayoutSlide) | Adds a copy of a specified slide to the end of the collection. |
| [AddClone](addclone)(ISlide, ISection) | Adds a copy of a specified slide to the end of the specified section. |
| [AddClone](addclone)(ISlide, IMasterSlide, bool) | Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [AddEmptySlide](addemptyslide)(ILayoutSlide) | Adds a new empty slide to the end of the collection. |
| [AddFromHtml](addfromhtml)(Stream) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](addfromhtml)(string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](addfromhtml)(TextReader) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](addfromhtml)(Stream, IExternalResourceResolver, string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](addfromhtml)(string, IExternalResourceResolver, string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](addfromhtml)(TextReader, IExternalResourceResolver, string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromPdf](addfrompdf)(Stream) | Creates slides from the PDF document and adds them to the end of the collection. |
| [AddFromPdf](addfrompdf)(string) | Creates slides from the PDF document and adds them to the end of the collection. |
| [IndexOf](indexof)(ISlide) | Returns an index of the specified slide in the collection. |
| [InsertClone](insertclone)(int, ISlide) | Inserts a copy of a specified slide to specified position of the collection. |
| [InsertClone](insertclone)(int, ISlide, ILayoutSlide) | Inserts a copy of a specified slide to specified position of the collection. |
| [InsertClone](insertclone)(int, ISlide, IMasterSlide, bool) | Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [InsertEmptySlide](insertemptyslide)(int, ILayoutSlide) | Inserts a copy of a specified slide to specified position of the collection. |
| [InsertFromHtml](insertfromhtml)(int, Stream) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](insertfromhtml)(int, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](insertfromhtml)(int, TextReader) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](insertfromhtml)(int, Stream, IExternalResourceResolver, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](insertfromhtml)(int, string, IExternalResourceResolver, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](insertfromhtml)(int, TextReader, IExternalResourceResolver, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [Remove](remove)(ISlide) | Removes the first occurrence of a specific object from the collection. |
| [RemoveAt](removeat)(int) | Removes the element at the specified index of the collection. |
| [Reorder](reorder)(int, ISlide) | Moves slide from the collection to the specified position. |
| [Reorder](reorder)(int, params ISlide[]) | Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list. |
| [ToArray](toarray)() | Creates and returns an array with all slides in it. |
| [ToArray](toarray)(int, int) | Creates and returns an array with all slides from the specified range in it. |

### See Also

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
