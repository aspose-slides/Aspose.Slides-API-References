---
title: SlideCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slidecollection/
---

## SlideCollection class

 Represents a collection of a slides.
 
### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Slide](../slide)) | Adds a copy of a specified slide to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #addClone(ISlide,ILayoutSlide) or #addClone(ISlide,IMasterSlide,boolean) for cloning slides, IGlobalLayoutSlideCollection#addClone(ILayoutSlide) or IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) for cloning layouts and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

 **Result:**
[Slide](../slide)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Slide](../slide), [Section](../section)) | Adds a copy of a specified slide to the end of the specified section. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| section | [Section](../section) | Section for a new slide. |

 **Result:**
[Slide](../slide)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | When section parameter contains wrong or invalid value. |


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Slide](../slide), [LayoutSlide](../layoutslide)) | Adds a copy of a specified slide to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destLayout | [LayoutSlide](../layoutslide) | Layout slide for a new slide. |

 **Result:**
[Slide](../slide)


---


### addClone {#addClone}

| Name | Description |
| --- | --- |
| addClone ([Slide](../slide), [MasterSlide](../masterslide), boolean) | Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destMaster | [MasterSlide](../masterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

 **Result:**
[Slide](../slide)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


### addEmptySlide {#addEmptySlide}

| Name | Description |
| --- | --- |
| addEmptySlide ([LayoutSlide](../layoutslide)) | Adds a new empty slide to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| layout | [LayoutSlide](../layoutslide) | Layout for a slide. |

 **Result:**
[Slide](../slide)


---


### addFromHtml {#addFromHtml}

| Name | Description |
| --- | --- |
| addFromHtml (String, [ExternalResourceResolver](../externalresourceresolver), String) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### addFromHtml {#addFromHtml}

| Name | Description |
| --- | --- |
| addFromHtml (String, [HtmlExternalResolver](../htmlexternalresolver), String) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### addFromHtml {#addFromHtml}

| Name | Description |
| --- | --- |
| addFromHtml (String) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| htmlText | String | Html to add. |

 **Result:**
[Slide](../slide)


---


### addFromHtmlFromStream  {#addFromHtmlFromStream }

| Name | Description |
| --- | --- |
| addFromHtmlFromStream  (SlideCollection, ReadStream, [ExternalResourceResolver](../externalresourceresolver),  String, Function) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[Slide](../slide)


---


### addFromHtmlFromStream  {#addFromHtmlFromStream }

| Name | Description |
| --- | --- |
| addFromHtmlFromStream  (SlideCollection, ReadStream, [HtmlExternalResolver](../htmlexternalresolver), String,  Function) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[Slide](../slide)


---


### addFromHtmlFromStream  {#addFromHtmlFromStream }

| Name | Description |
| --- | --- |
| addFromHtmlFromStream  (SlideCollection, ReadStream, Function) | Creates slides from HTML text and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[Slide](../slide)


---


### addFromPdf {#addFromPdf}

| Name | Description |
| --- | --- |
| addFromPdf (String) | Creates slides from the PDF document and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | A path to the PDF document |

 **Result:**
[Slide](../slide)


---


### addFromPdf {#addFromPdf}

| Name | Description |
| --- | --- |
| addFromPdf (String, [PdfImportOptions](../pdfimportoptions)) | Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| path | String | A path to the PDF document |
| pdfImportOptions | [PdfImportOptions](../pdfimportoptions) | Options for pdf import |

 **Result:**
[Slide](../slide)


---


### addFromPdfFromStream  {#addFromPdfFromStream }

| Name | Description |
| --- | --- |
| addFromPdfFromStream  (SlideCollection, ReadStream, Function) | Creates slides from the PDF document and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| pdfStream | ReadStream | A stream which will be used as a source of the PDF document |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[Slide](../slide)


---


### addFromPdfFromStream  {#addFromPdfFromStream }

| Name | Description |
| --- | --- |
| addFromPdfFromStream  (SlideCollection, ReadStream, [PdfImportOptions](../pdfimportoptions), Function) | Creates slides from the PDF document and adds them to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| pdfStream | ReadStream | A stream which will be used as a source of the PDF document |
| pdfImportOptions | [PdfImportOptions](../pdfimportoptions) | Options for pdf import |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[Slide](../slide)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Result:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. Read-only Slide. |

 **Result:**
[Slide](../slide)


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Slide](../slide)) | Returns an index of the specified slide in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slide | [Slide](../slide) | Slide to find. |

 **Result:**
int


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Slide](../slide)) | Inserts a copy of a specified slide to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [Slide](../slide) | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #insertClone(int,ISlide,ILayoutSlide) or #insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

 **Result:**
[Slide](../slide)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Slide](../slide), [LayoutSlide](../layoutslide)) | Inserts a copy of a specified slide to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destLayout | [LayoutSlide](../layoutslide) | Layout slide for a new slide. |

 **Result:**
[Slide](../slide)


---


### insertClone {#insertClone}

| Name | Description |
| --- | --- |
| insertClone (int, [Slide](../slide), [MasterSlide](../masterslide), boolean) | Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceSlide | [Slide](../slide) | Slide to clone. |
| destMaster | [MasterSlide](../masterslide) | Master slide for a new slide. |
| allowCloneMissingLayout | boolean | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

 **Result:**
[Slide](../slide)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


### insertEmptySlide {#insertEmptySlide}

| Name | Description |
| --- | --- |
| insertEmptySlide (int, [LayoutSlide](../layoutslide)) | Inserts a copy of a specified slide to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a new slide. |
| layout | [LayoutSlide](../layoutslide) | Layout for a slide. |

 **Result:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String, [ExternalResourceResolver](../externalresourceresolver), String) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | String | Html to add. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String, [HtmlExternalResolver](../htmlexternalresolver), String) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | String | Html to add. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |

 **Result:**
[Slide](../slide)


---


### insertFromHtml {#insertFromHtml}

| Name | Description |
| --- | --- |
| insertFromHtml (int, String) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Position to insert. |
| htmlText | String | Html to add. |

 **Result:**
[Slide](../slide)


---


### insertFromHtmlFromStream  {#insertFromHtmlFromStream }

| Name | Description |
| --- | --- |
| insertFromHtmlFromStream  (SlideCollection, int, ReadStream,  [ExternalResourceResolver](../externalresourceresolver), String, Function) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| index | int | Position to insert. |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [ExternalResourceResolver](../externalresourceresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[Slide](../slide)


---


### insertFromHtmlFromStream  {#insertFromHtmlFromStream }

| Name | Description |
| --- | --- |
| insertFromHtmlFromStream  (SlideCollection, int, ReadStream, [HtmlExternalResolver](../htmlexternalresolver),  String, Function) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| index | int | Position to insert. |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| resolver | [HtmlExternalResolver](../htmlexternalresolver) | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | String | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[Slide](../slide)


---


### insertFromHtmlFromStream  {#insertFromHtmlFromStream }

| Name | Description |
| --- | --- |
| insertFromHtmlFromStream  (SlideCollection, int, ReadStream, Function) | Creates slides from HTML text and inserts them to the collection at the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| index | int | Position to insert. |
| htmlStream | ReadStream | A Stream object which will be used as a source of a HTML file. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

 **Result:**
[Slide](../slide)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Result:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Result:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Result:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Slide](../slide)) | Removes the first occurrence of a specific object from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| value | [Slide](../slide) | The slide to remove from the collection. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes the element at the specified index of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | When index parameter contains wrong section number. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, [Slide](../slide)) | Moves slide from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| slide | [Slide](../slide) | Slide to move. |


---


### reorder {#reorder}

| Name | Description |
| --- | --- |
| reorder (int, com.aspose.slides.ISlide[]) | Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Target index. |
| slides | com.aspose.slides.ISlide[] | Slides to move. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Gets the number of elements actually contained in the collection. Read-only int. |

 **Result:**
int


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray () | Creates and returns an array with all slides in it. |

 **Result:**
[Slide](../slide)


---


### toArray {#toArray}

| Name | Description |
| --- | --- |
| toArray (int, int) | Creates and returns an array with all slides from the specified range in it. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first slide to add. |
| count | int | A number of slides to add. |

 **Result:**
[Slide](../slide)


---


