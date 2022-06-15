---
title: SlideCollection
type: docs
weight: 0
url: /php-java/slidecollection/
---

# SlideCollection class

 Represents a collection of a slides.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [addClone](/php-java/slidecollection/addclone/)(ISlide) | ISlide | Adds a copy of a specified slide to the end of the collection. |
| [addClone](/php-java/slidecollection/addclone/)(ISlide, ISection) | ISlide | Adds a copy of a specified slide to the end of the specified section. |
| [addClone](/php-java/slidecollection/addclone/)(ISlide, ILayoutSlide) | ISlide | Adds a copy of a specified slide to the end of the collection. |
| [addClone](/php-java/slidecollection/addclone/)(ISlide, IMasterSlide, boolean) | ISlide | Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [addEmptySlide](/php-java/slidecollection/addemptyslide/)(ILayoutSlide) | ISlide | Adds a new empty slide to the end of the collection. |
| [addFromHtml](/php-java/slidecollection/addfromhtml/)(String, IExternalResourceResolver, String) | ISlide | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml](/php-java/slidecollection/addfromhtml/)(String) | ISlide | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml](/php-java/slidecollection/addfromhtml/)(InputStream, IExternalResourceResolver, String) | ISlide | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml](/php-java/slidecollection/addfromhtml/)(InputStream) | ISlide | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromPdf](/php-java/slidecollection/addfrompdf/)(String) | ISlide | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromPdf](/php-java/slidecollection/addfrompdf/)(InputStream) | ISlide | Creates slides from the PDF document and adds them to the end of the collection. |
| [getSyncRoot](/php-java/slidecollection/getsyncroot/)() | Object | Returns a synchronization root. Read-only Object. |
| [get_Item](/php-java/slidecollection/get_item/)(int) | ISlide | Gets the element at the specified index. Read-only Slide. |
| [indexOf](/php-java/slidecollection/indexof/)(ISlide) | int | Returns an index of the specified slide in the collection. |
| [insertClone](/php-java/slidecollection/insertclone/)(int, ISlide) | ISlide | Inserts a copy of a specified slide to specified position of the collection. |
| [insertClone](/php-java/slidecollection/insertclone/)(int, ISlide, ILayoutSlide) | ISlide | Inserts a copy of a specified slide to specified position of the collection. |
| [insertClone](/php-java/slidecollection/insertclone/)(int, ISlide, IMasterSlide, boolean) | ISlide | Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |
| [insertEmptySlide](/php-java/slidecollection/insertemptyslide/)(int, ILayoutSlide) | ISlide | Inserts a copy of a specified slide to specified position of the collection. |
| [insertFromHtml](/php-java/slidecollection/insertfromhtml/)(int, String, IExternalResourceResolver, String) | ISlide | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml](/php-java/slidecollection/insertfromhtml/)(int, String) | ISlide | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml](/php-java/slidecollection/insertfromhtml/)(int, InputStream, IExternalResourceResolver, String) | ISlide | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml](/php-java/slidecollection/insertfromhtml/)(int, InputStream) | ISlide | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [isSynchronized](/php-java/slidecollection/issynchronized/)() | boolean | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |
| [iterator](/php-java/slidecollection/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/slidecollection/iteratorjava/)() | IGenericEnumerator | Returns a java iterator for the entire collection. |
| [remove](/php-java/slidecollection/remove/)(ISlide) | void | Removes the first occurrence of a specific object from the collection. |
| [removeAt](/php-java/slidecollection/removeat/)(int) | void | Removes the element at the specified index of the collection. |
| [reorder](/php-java/slidecollection/reorder/)(int, ISlide) | void | Moves slide from the collection to the specified position. |
| [reorder](/php-java/slidecollection/reorder/)(int, com.aspose.slides.ISlide[]) | void | Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list. |
| [size](/php-java/slidecollection/size/)() | int | Gets the number of elements actually contained in the collection. Read-only int. |
| [toArray](/php-java/slidecollection/toarray/)() | ISlide | Creates and returns an array with all slides in it. |
| [toArray](/php-java/slidecollection/toarray/)(int, int) | ISlide | Creates and returns an array with all slides from the specified range in it. |
