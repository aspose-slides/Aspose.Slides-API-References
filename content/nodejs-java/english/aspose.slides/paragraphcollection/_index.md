---
title: ParagraphCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/paragraphcollection/
---

## ParagraphCollection class

 Represents a collection of a paragraphs.
 
| [add] ([Paragraph]) | Adds a Paragraph to the end of collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [Paragraph] | The Paragraph to be added to the end of the collection. |


---


| [add] ([ParagraphCollection]) | Adds a content of ParagraphCollection to the end of collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [ParagraphCollection] | The ParagraphCollection to be added to the end of the collection. |

### Result
int


---


| [addFromHtml] ([String]) | Adds text from specified html string to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | [String] | HTML text. |


---


| [addFromHtml] ([String], [ExternalResourceResolver], [String]) | Adds text from specified html string to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | [String] | HTML text. |
| resolver | [ExternalResourceResolver] | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | [String] | URI for adding HTML document. Used for resolving relative links. Specifying resolver can potentially introduce a vulnurability. Use with caution. |


---


| [addFromHtml] ([String], [HtmlExternalResolver], [String]) | Adds text from specified html string to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | [String] | HTML text. |
| resolver | [HtmlExternalResolver] | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | [String] | URI for adding HTML document. Used for resolving relative links. Specifying resolver can potentially introduce a vulnurability. Use with caution. |


---


| [clear] () | Removes all elements from the collection. |


---


| [contains] ([Paragraph]) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Paragraph] | The object to locate in the IGenericCollection. |

### Result
boolean


---


| [copyTo] ([com.aspose.slides.IParagraph[]], [int]) | Copies the elements of the IGenericCollection to an Array, starting at a particular Array index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| array | [com.aspose.slides.IParagraph[]] | The one-dimensional Array that is the destination of the elements copied from IGenericCollection. The Array must have zero-based indexing. |
| arrayIndex | [int] | The zero-based index in array at which copying begins. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | The number of elements in the source IGenericCollection is greater than the available space from arrayIndex to the end of the destination array. |


---


| [exportToHtml] ([int], [int], [TextToHtmlConversionOptions]) | Converts specifying paragraphs to the HTML and returns it as String object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | [int] | First paragraph index int |
| paragraphsCount | [int] | Paragraph count int |
| options | [TextToHtmlConversionOptions] | Convert options ITextToHtmlConversionOptions |

### Result
String


---


| [getCount] () | Gets the number of elements actually contained in the collection. Read-only int. |

### Result
int


---


| [getPresentation] () | Returns the parent presentation of a paragraphs collection. Read-only IPresentation. |

### Result
[Presentation]


---


| [getSlide] () | Returns the parent slide of a paragraphs collection. Read-only BaseSlide. |

### Result
[MasterNotesSlide], [MasterHandoutSlide], [BaseSlide], [NotesSlide], [LayoutSlide], [Slide], [MasterSlide]


---


| [get_Item] ([int]) | Gets the element at the specified index. |

### Result
[Paragraph]


---


| [indexOf] ([Paragraph]) | Determines the index of a specific item in the List. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Paragraph] | The object to locate in the List. |

### Result
int


---


| [insert] ([int], [Paragraph]) | Inserts a Paragraph into the collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which Paragraph should be inserted. |
| value | [Paragraph] | The Paragraph to insert. |


---


| [insert] ([int], [ParagraphCollection]) | Inserts a content of ParagraphCollection into the collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which paragraphs should be inserted. |
| value | [ParagraphCollection] | The paragraphs to insert. |


---


| [isReadOnly] () | Gets a value indicating whether the IGenericCollection is read-only. Read-only boolean. |

### Result
boolean


---


| [iterator] () | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () | Returns a java iterator for the entire collection. |

### Result



---


| [remove] ([Paragraph]) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Paragraph] | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| [removeAt] ([int]) | Removes the element at the specified index of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index of the element to remove. |


---


