---
title: ParagraphCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of a paragraphs.
type: docs
weight: 400
url: /com.aspose.slides/paragraphcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection), com.aspose.slides.IObserver
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection, IObserver
```

Represents a collection of a paragraphs.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Adds a Paragraph to the end of collection. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Adds a content of ParagraphCollection to the end of collection. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Determines the index of a specific item in the List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Inserts a Paragraph into the collection at the specified index. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Inserts a content of ParagraphCollection into the collection at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Removes the first occurrence of a specific object from the [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getSlide()](#getSlide--) | Returns the parent slide of a paragraphs collection. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a paragraphs collection. |
| [notify(Object sender)](#notify-java.lang.Object-) |  |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Adds text from specified html string to the collection. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Adds text from specified html string to the collection. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Converts specifying paragraphs to the HTML and returns it as String object. |
### getCount() {#getCount--}
```
public final int getCount()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. Read-only boolean.

**Returns:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```


Adds a Paragraph to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | The Paragraph to be added to the end of the collection. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```


Adds a content of ParagraphCollection to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | The ParagraphCollection to be added to the end of the collection. |

**Returns:**
int - The index at which the Paragraph has been added or -1 if there are nothing to add.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```


Determines the index of a specific item in the List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | The object to locate in the List. |

**Returns:**
int - The index of item if found in the list; otherwise, -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```


Inserts a Paragraph into the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Paragraph should be inserted. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | The Paragraph to insert. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```


Inserts a content of ParagraphCollection into the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which paragraphs should be inserted. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | The paragraphs to insert. |

### clear() {#clear--}
```
public final void clear()
```


Removes all elements from the collection.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```


Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | The object to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```


Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | The one-dimensional Array that is the destination of the elements copied from [IGenericCollection](../../com.aspose.slides/igenericcollection). The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```


Removes the first occurrence of a specific object from the [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | The object to remove from the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if item was successfully removed from the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false. This method also returns false if item is not found in the original [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - An java.util.Iterator for the entire collection.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a paragraphs collection. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a paragraphs collection. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### notify(Object sender) {#notify-java.lang.Object-}
```
public final void notify(Object sender)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sender | java.lang.Object |  |

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```


Adds text from specified html string to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | HTML text. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Adds text from specified html string to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | HTML text. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | java.lang.String | URI for adding HTML document. Used for resolving relative links.

--------------------

Specifying resolver can potentially introduce a vulnurability. Use with caution. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


Converts specifying paragraphs to the HTML and returns it as String object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | First paragraph index int |
| paragraphsCount | int | Paragraph count int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Convert options [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Returns:**
java.lang.String - Generated HTML.
