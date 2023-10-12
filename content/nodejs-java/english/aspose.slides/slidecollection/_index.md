---
title: SlideCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slidecollection/
---

## SlideCollection class

 Represents a collection of a slides.
 
| [addClone] ([Slide]) | Adds a copy of a specified slide to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide] | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #addClone(ISlide,ILayoutSlide) or #addClone(ISlide,IMasterSlide,boolean) for cloning slides, IGlobalLayoutSlideCollection#addClone(ILayoutSlide) or IGlobalLayoutSlideCollection#addClone(ILayoutSlide,IMasterSlide) for cloning layouts and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

### Result
[Slide]


---


| [addClone] ([Slide], [Section]) | Adds a copy of a specified slide to the end of the specified section. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide] | Slide to clone. |
| section | [Section] | Section for a new slide. |

### Result
[Slide]

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | When section parameter contains wrong or invalid value. |


---


| [addClone] ([Slide], [LayoutSlide]) | Adds a copy of a specified slide to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide] | Slide to clone. |
| destLayout | [LayoutSlide] | Layout slide for a new slide. |

### Result
[Slide]


---


| [addClone] ([Slide], [MasterSlide], [boolean]) | Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceSlide | [Slide] | Slide to clone. |
| destMaster | [MasterSlide] | Master slide for a new slide. |
| allowCloneMissingLayout | [boolean] | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Result
[Slide]

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


| [addEmptySlide] ([LayoutSlide]) | Adds a new empty slide to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| layout | [LayoutSlide] | Layout for a slide. |

### Result
[Slide]


---


| [addFromHtml] ([String], [ExternalResourceResolver], [String]) | Creates slides from HTML text and adds them to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| htmlText | [String] | Html to add. |
| resolver | [ExternalResourceResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [String] | An URI of the specified HTML. Used to resolve relative links. |

### Result
[Slide]


---


| [addFromHtml] ([String], [HtmlExternalResolver], [String]) | Creates slides from HTML text and adds them to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| htmlText | [String] | Html to add. |
| resolver | [HtmlExternalResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [String] | An URI of the specified HTML. Used to resolve relative links. |

### Result
[Slide]


---


| [addFromHtml] ([String]) | Creates slides from HTML text and adds them to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| htmlText | [String] | Html to add. |

### Result
[Slide]


---


| [addFromHtmlFromStream ] (SlideCollection, [ReadStream], [ExternalResourceResolver],  [String], Function) | Creates slides from HTML text and adds them to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| htmlStream | [ReadStream] | A Stream object which will be used as a source of a HTML file. |
| resolver | [ExternalResourceResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [String] | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide]


---


| [addFromHtmlFromStream ] (SlideCollection, [ReadStream], [HtmlExternalResolver], [String],  Function) | Creates slides from HTML text and adds them to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| htmlStream | [ReadStream] | A Stream object which will be used as a source of a HTML file. |
| resolver | [HtmlExternalResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [String] | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide]


---


| [addFromHtmlFromStream ] (SlideCollection, [ReadStream], Function) | Creates slides from HTML text and adds them to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| htmlStream | [ReadStream] | A Stream object which will be used as a source of a HTML file. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide]


---


| [addFromPdf] ([String]) | Creates slides from the PDF document and adds them to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| path | [String] | A path to the PDF document |

### Result
[Slide]


---


| [addFromPdfFromStream ] (SlideCollection, [ReadStream], Function) | Creates slides from the PDF document and adds them to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| pdfStream | [ReadStream] | A stream which will be used as a source of the PDF document |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide]


---


| [getSyncRoot] () | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item] ([int]) | Gets the element at the specified index. Read-only Slide. |

### Result
[Slide]


---


| [indexOf] ([Slide]) | Returns an index of the specified slide in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slide | [Slide] | Slide to find. |

### Result
int


---


| [insertClone] ([int], [Slide]) | Inserts a copy of a specified slide to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new slide. |
| sourceSlide | [Slide] | Slide to clone. When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use #insertClone(int,ISlide,ILayoutSlide) or #insertClone(int,ISlide,IMasterSlide,boolean) for cloning slides and IMasterSlideCollection#addClone(IMasterSlide) for cloning masters. |

### Result
[Slide]


---


| [insertClone] ([int], [Slide], [LayoutSlide]) | Inserts a copy of a specified slide to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new slide. |
| sourceSlide | [Slide] | Slide to clone. |
| destLayout | [LayoutSlide] | Layout slide for a new slide. |

### Result
[Slide]


---


| [insertClone] ([int], [Slide], [MasterSlide], [boolean]) | Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new slide. |
| sourceSlide | [Slide] | Slide to clone. |
| destMaster | [MasterSlide] | Master slide for a new slide. |
| allowCloneMissingLayout | [boolean] | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Result
[Slide]

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if there is no appropriate layout in specified master and allowCloneMissingLayout is false. |


---


| [insertEmptySlide] ([int], [LayoutSlide]) | Inserts a copy of a specified slide to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of a new slide. |
| layout | [LayoutSlide] | Layout for a slide. |

### Result
[Slide]


---


| [insertFromHtml] ([int], [String], [ExternalResourceResolver], [String]) | Creates slides from HTML text and inserts them to the collection at the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Position to insert. |
| htmlText | [String] | Html to add. |
| resolver | [ExternalResourceResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [String] | An URI of the specified HTML. Used to resolve relative links. |

### Result
[Slide]


---


| [insertFromHtml] ([int], [String], [HtmlExternalResolver], [String]) | Creates slides from HTML text and inserts them to the collection at the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Position to insert. |
| htmlText | [String] | Html to add. |
| resolver | [HtmlExternalResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [String] | An URI of the specified HTML. Used to resolve relative links. |

### Result
[Slide]


---


| [insertFromHtml] ([int], [String]) | Creates slides from HTML text and inserts them to the collection at the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Position to insert. |
| htmlText | [String] | Html to add. |

### Result
[Slide]


---


| [insertFromHtmlFromStream ] (SlideCollection, [int], [ReadStream],  [ExternalResourceResolver], [String], Function) | Creates slides from HTML text and inserts them to the collection at the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| index | [int] | Position to insert. |
| htmlStream | [ReadStream] | A Stream object which will be used as a source of a HTML file. |
| resolver | [ExternalResourceResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [String] | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide]


---


| [insertFromHtmlFromStream ] (SlideCollection, [int], [ReadStream], [HtmlExternalResolver],  [String], Function) | Creates slides from HTML text and inserts them to the collection at the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| index | [int] | Position to insert. |
| htmlStream | [ReadStream] | A Stream object which will be used as a source of a HTML file. |
| resolver | [HtmlExternalResolver] | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [String] | An URI of the specified HTML. Used to resolve relative links. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide]


---


| [insertFromHtmlFromStream ] (SlideCollection, [int], [ReadStream], Function) | Creates slides from HTML text and inserts them to the collection at the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| slidecollection | SlideCollection  | link to self |
| index | [int] | Position to insert. |
| htmlStream | [ReadStream] | A Stream object which will be used as a source of a HTML file. |
| callback | Function | callback(error, result) - Callback to be called when the method has completed |

### Result
[Slide]


---


| [isSynchronized] () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator] () | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () | Returns a java iterator for the entire collection. |

### Result



---


| [remove] ([Slide]) | Removes the first occurrence of a specific object from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [Slide] | The slide to remove from the collection. |


---


| [removeAt] ([int]) | Removes the element at the specified index of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index of the element to remove. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | When index parameter contains wrong section number. |


---


| [reorder] ([int], [Slide]) | Moves slide from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| slide | [Slide] | Slide to move. |


---


| [reorder] ([int], [com.aspose.slides.ISlide[]]) | Moves slides from the collection to the specified position. Slides will be placed starting from index in order they appear in list. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Target index. |
| slides | [com.aspose.slides.ISlide[]] | Slides to move. |


---


| [size] () | Gets the number of elements actually contained in the collection. Read-only int. |

### Result
int


---


| [toArray] () | Creates and returns an array with all slides in it. |

### Result
[Slide]


---


| [toArray] ([int], [int]) | Creates and returns an array with all slides from the specified range in it. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| startIndex | [int] | An index of a first slide to add. |
| count | [int] | A number of slides to add. |

### Result
[Slide]


---


