---
title: SlideCollection
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 9190
url: /net/aspose.slides/slidecollection/
---
## SlideCollection class

Represents a collection of a slides.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Properties

| Name | Description |
| --- | --- |
| [Count](count) { get; } | Gets the number of elements actually contained in the collection. Read-only Int32. |
| [IsSynchronized](issynchronized) { get; } | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only Boolean. |
| [Item](item) { get; } | Gets the element at the specified index. Read-only [`Slide`](../slide). |
| [SyncRoot](syncroot) { get; } | Returns a synchronization root. Read-only Object. |

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
| [CopyTo](copyto)(Array, int) | Copies all elements from the collection to the specified array. |
| [GetEnumerator](getenumerator)() | Returns an enumerator that iterates through the collection. |
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
| [ToArray](toarray)(int, int) | Creates and returns an array with all slides from the specified range in it. An index of a first slide to add.A number of slides to add. |

### See Also

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [ISlideCollection](../islidecollection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
