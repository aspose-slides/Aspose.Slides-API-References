---
title: SlideCollection
second_title: Aspose.Sildes for .NET API Reference
description: Represents a collection of a slides.
type: docs
weight: 9660
url: /aspose.slides/slidecollection/
---

## SlideCollection class

Represents a collection of a slides.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Gets the number of elements actually contained in the collection. Read-only Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Gets the element at the specified index. Read-only [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Returns a synchronization root. Read-only Object. |

## Methods

| Name | Description |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Adds a copy of a specified slide to the end of the collection. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Adds a copy of a specified slide to the end of the collection. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Adds a copy of a specified slide to the end of the specified section. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Adds a new empty slide to the end of the collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Creates slides from HTML text and adds them to the end of the collection. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Creates slides from the PDF document and adds them to the end of the collection. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Creates slides from the PDF document and adds them to the end of the collection. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Creates slides from the PDF document and adds them to the end of the collection. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Copies all elements from the collection to the specified array. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Returns an enumerator that iterates through the collection. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Returns an index of the specified slide in the collection. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Inserts a copy of a specified slide to specified position of the collection. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Inserts a copy of a specified slide to specified position of the collection. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Inserts a copy of a specified slide to specified position of the collection. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Removes the first occurrence of a specific object from the collection. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Removes the element at the specified index of the collection. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Moves slide from the collection to the specified position. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Creates and returns an array with all slides in it. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Creates and returns an array with all slides from the specified range in it. An index of a first slide to add.A number of slides to add. |

### See Also

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [ISlideCollection](../islidecollection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
