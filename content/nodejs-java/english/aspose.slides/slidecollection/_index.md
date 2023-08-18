---
title: SlideCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slidecollection/
---

## SlideCollection class

 Represents a collection of a slides.
 

## Functions

| Name | Description |
| --- | --- |
| [addClone](addclone)([Slide](../slide)) | Adds a copy of a specified slide to the end of the collection. |
| [addClone](addclone)([Slide](../slide), [Section](../section)) | Adds a copy of a specified slide to the end of the specified section. |
| [addClone](addclone)([Slide](../slide), [LayoutSlide](../layoutslide)) | Adds a copy of a specified slide to the end of the collection. |
| [addClone](addclone)([Slide](../slide), [MasterSlide](../masterslide), boolean) | Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [addEmptySlide](addemptyslide)([LayoutSlide](../layoutslide)) | Adds a new empty slide to the end of the collection. |
| [addFromHtml](addfromhtml)(String, [ExternalResourceResolver](../externalresourceresolver), String) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml](addfromhtml)(String, [HtmlExternalResolver](../htmlexternalresolver), String) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml](addfromhtml)(String) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtmlFromStream ](addfromhtml)(SlideCollection, ReadStream, [ExternalResourceResolver](../externalresourceresolver),  String, Function) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtmlFromStream ](addfromhtml)(SlideCollection, ReadStream, [HtmlExternalResolver](../htmlexternalresolver), String,  Function) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtmlFromStream ](addfromhtml)(SlideCollection, ReadStream, Function) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromPdf](addfrompdf)(String) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromPdfFromStream ](addfrompdf)(SlideCollection, ReadStream, Function) | Creates slides from the PDF document and adds them to the end of the collection. |
| [getSyncRoot](getsyncroot)() | Returns a synchronization root. Read-only Object. |
| [get_Item](get_item)(int) | Gets the element at the specified index. Read-only Slide. |
| [indexOf](indexof)([Slide](../slide)) | Returns an index of the specified slide in the collection. |
| [insertClone](insertclone)(int, [Slide](../slide)) | Inserts a copy of a specified slide to specified position of the collection. |
| [insertClone](insertclone)(int, [Slide](../slide), [LayoutSlide](../layoutslide)) | Inserts a copy of a specified slide to specified position of the collection. |
| [insertClone](insertclone)(int, [Slide](../slide), [MasterSlide](../masterslide), boolean) | Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [insertEmptySlide](insertemptyslide)(int, [LayoutSlide](../layoutslide)) | Inserts a copy of a specified slide to specified position of the collection. |
| [insertFromHtml](insertfromhtml)(int, String, [ExternalResourceResolver](../externalresourceresolver), String) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml](insertfromhtml)(int, String, [HtmlExternalResolver](../htmlexternalresolver), String) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml](insertfromhtml)(int, String) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtmlFromStream ](insertfromhtml)(SlideCollection, int, ReadStream,  [ExternalResourceResolver](../externalresourceresolver), String, Function) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtmlFromStream ](insertfromhtml)(SlideCollection, int, ReadStream, [HtmlExternalResolver](../htmlexternalresolver),  String, Function) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtmlFromStream ](insertfromhtml)(SlideCollection, int, ReadStream, Function) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [isSynchronized](issynchronized)() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](iterator)() | Returns an enumerator that iterates through the collection. |
| [iteratorJava](iteratorjava)() | Returns a java iterator for the entire collection. |
| [remove](remove)([Slide](../slide)) | Removes the first occurrence of a specific object from the collection. |
| [removeAt](removeat)(int) | Removes the element at the specified index of the collection. |
| [reorder](reorder)(int, [Slide](../slide)) | Moves slide from the collection to the specified position. |
| [reorder](reorder)(int, com.aspose.slides.ISlide[]) | Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list. |
| [size](size)() | Gets the number of elements actually contained in the collection. Read-only int. |
| [toArray](toarray)() | Creates and returns an array with all slides in it. |
| [toArray](toarray)(int, int) | Creates and returns an array with all slides from the specified range in it. |
