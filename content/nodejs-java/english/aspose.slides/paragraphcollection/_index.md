---
title: ParagraphCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/paragraphcollection/
---

## ParagraphCollection class

 Represents a collection of a paragraphs.
 
| Name | Description |
| --- | --- |
| add (Paragraph(../paragraph)) | Adds a Paragraph to the end of collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | Paragraph(../../paragraph) | The Paragraph to be added to the end of the collection. |


---


| Name | Description |
| --- | --- |
| add (ParagraphCollection(../paragraphcollection)) | Adds a content of ParagraphCollection to the end of collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | ParagraphCollection(../../paragraphcollection) | The ParagraphCollection to be added to the end of the collection. |

### Result
int


---


| Name | Description |
| --- | --- |
| addFromHtml (String) | Adds text from specified html string to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | String | HTML text. |


---


| Name | Description |
| --- | --- |
| addFromHtml (String, ExternalResourceResolver(../externalresourceresolver), String) | Adds text from specified html string to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | String | HTML text. |
| resolver | ExternalResourceResolver(../externalresourceresolver) | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | String | URI for adding HTML document. Used for resolving relative links. Specifying resolver can potentially introduce a vulnurability. Use with caution. |


---


| Name | Description |
| --- | --- |
| addFromHtml (String, HtmlExternalResolver(../htmlexternalresolver), String) | Adds text from specified html string to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| text | String | HTML text. |
| resolver | HtmlExternalResolver(../htmlexternalresolver) | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | String | URI for adding HTML document. Used for resolving relative links. Specifying resolver can potentially introduce a vulnurability. Use with caution. |


---


| Name | Description |
| --- | --- |
| clear () | Removes all elements from the collection. |


---


| Name | Description |
| --- | --- |
| contains (Paragraph(../paragraph)) | Determines whether the IGenericCollection contains a specific value. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | Paragraph(../../paragraph) | The object to locate in the IGenericCollection. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| copyTo (com.aspose.slides.IParagraph[], int) | Copies the elements of the IGenericCollection to an Array, starting at a particular Array index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| array | com.aspose.slides.IParagraph[] | The one-dimensional Array that is the destination of the elements copied from IGenericCollection. The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | The number of elements in the source IGenericCollection is greater than the available space from arrayIndex to the end of the destination array. |


---


| Name | Description |
| --- | --- |
| exportToHtml (int, int, TextToHtmlConversionOptions(../texttohtmlconversionoptions)) | Converts specifying paragraphs to the HTML and returns it as String object. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | First paragraph index int |
| paragraphsCount | int | Paragraph count int |
| options | TextToHtmlConversionOptions(../../texttohtmlconversionoptions) | Convert options ITextToHtmlConversionOptions |

### Result
String


---


| Name | Description |
| --- | --- |
| getCount () | Gets the number of elements actually contained in the collection. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a paragraphs collection. Read-only IPresentation. |

### Result
Presentation(../../presentation)


---


| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a paragraphs collection. Read-only BaseSlide. |

### Result
MasterNotesSlide(../../masternotesslide), MasterHandoutSlide(../../masterhandoutslide), BaseSlide(../../baseslide), NotesSlide(../../notesslide), LayoutSlide(../../layoutslide), Slide(../../slide), MasterSlide(../../masterslide)


---


| Name | Description |
| --- | --- |
| get_Item (int) | Gets the element at the specified index. |

### Result
Paragraph(../../paragraph)


---


| Name | Description |
| --- | --- |
| indexOf (Paragraph(../paragraph)) | Determines the index of a specific item in the List. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | Paragraph(../../paragraph) | The object to locate in the List. |

### Result
int


---


| Name | Description |
| --- | --- |
| insert (int, Paragraph(../paragraph)) | Inserts a Paragraph into the collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Paragraph should be inserted. |
| value | Paragraph(../../paragraph) | The Paragraph to insert. |


---


| Name | Description |
| --- | --- |
| insert (int, ParagraphCollection(../paragraphcollection)) | Inserts a content of ParagraphCollection into the collection at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which paragraphs should be inserted. |
| value | ParagraphCollection(../../paragraphcollection) | The paragraphs to insert. |


---


| Name | Description |
| --- | --- |
| isReadOnly () | Gets a value indicating whether the IGenericCollection is read-only. Read-only boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

### Result



---


| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

### Result



---


| Name | Description |
| --- | --- |
| remove (Paragraph(../paragraph)) | Removes the first occurrence of a specific object from the IGenericCollection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | Paragraph(../../paragraph) | The object to remove from the IGenericCollection. |

### Result
boolean

### Error

| Error | Condition |
| --- | --- |
 | NotSupportedException | The IGenericCollection is read-only. |


---


| Name | Description |
| --- | --- |
| removeAt (int) | Removes the element at the specified index of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |


---


