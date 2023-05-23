---
title: ICommentAuthorCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a collection of comment authors.
type: docs
weight: 729
url: /androidjava/com.aspose.slides/icommentauthorcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Represents a collection of comment authors.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Add new author at the end of a collection. |
| [toArray()](#toArray--) | Creates and returns an array with all authors. |
| [findByName(String name)](#findByName-java.lang.String-) | Find author in a collection by name. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Find author in a collection by name and initials. |
| [removeAt(int index)](#removeAt-int-) | Removes the author at the specified index of the collection. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Removes the first occurrence of the specified author in a collection. |
| [clear()](#clear--) | Removes all authors from a collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Gets the element at the specified index. Read-only [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Add new author at the end of a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of a new author. |
| initials | java.lang.String | Initials of a new author. |

**Returns:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - New [ICommentAuthor](../../com.aspose.slides/icommentauthor) object.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Creates and returns an array with all authors.

**Returns:**
com.aspose.slides.ICommentAuthor[] - Array of [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Find author in a collection by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of an author to find. |

**Returns:**
com.aspose.slides.ICommentAuthor[] - Author or null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Find author in a collection by name and initials.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of an author to find. |
| initials | java.lang.String | Initials of an author to find. |

**Returns:**
com.aspose.slides.ICommentAuthor[] - Author or null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the author at the specified index of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Removes the first occurrence of the specified author in a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | The author to remove from a collection. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all authors from a collection.

