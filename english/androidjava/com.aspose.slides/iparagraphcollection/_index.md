---
title: IParagraphCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of a paragraphs.
type: docs
weight: 956
url: /androidjava/com.aspose.slides/iparagraphcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Represents a collection of a paragraphs.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Adds a Paragraph to the end of collection. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Adds a content of ParagraphCollection to the end of collection. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Inserts a Paragraph into the collection at the specified index. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Inserts a content of ParagraphCollection into the collection at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Removes the first occurrence of a specific paragraph. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Adds text from specified html string to the collection. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Adds text from specified html string to the collection. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Converts specifying paragraphs to the HTML and returns it as String object. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Returns:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


Adds a Paragraph to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | The Paragraph to be added to the end of the collection. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


Adds a content of ParagraphCollection to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | The ParagraphCollection to be added to the end of the collection. |

**Returns:**
int - The index at which the Paragraph has been added or -1 if there are nothing to add.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


Inserts a Paragraph into the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Paragraph should be inserted. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | The Paragraph to insert. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


Inserts a content of ParagraphCollection into the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which paragraphs should be inserted. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | The paragraphs to insert. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


Removes the first occurrence of a specific paragraph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | The paragraph to remove from collection. |

**Returns:**
boolean - true if item was successfully removed; otherwise, false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


Adds text from specified html string to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | HTML text. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
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
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
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
