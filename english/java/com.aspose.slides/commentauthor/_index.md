---
title: CommentAuthor
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents an author of comments.
type: docs
weight: 127
url: /java/com.aspose.slides/commentauthor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICommentAuthor](../../com.aspose.slides/icommentauthor), com.aspose.slides.IDOMObject
```
public final class CommentAuthor implements ICommentAuthor, IDOMObject
```

Represents an author of comments.
## Constructors

| Constructor | Description |
| --- | --- |
| [CommentAuthor(CommentAuthorCollection parentImmediate, long id, String name, String initials)](#CommentAuthor-com.aspose.slides.CommentAuthorCollection-long-java.lang.String-java.lang.String-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns or sets the author's name. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the author's name. |
| [getInitials()](#getInitials--) | Returns or sets the authors initials. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Returns or sets the authors initials. |
| [getComments()](#getComments--) | Returns the collection of comments made by this author. |
| [remove()](#remove--) | Removes the author from the parent collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### CommentAuthor(CommentAuthorCollection parentImmediate, long id, String name, String initials) {#CommentAuthor-com.aspose.slides.CommentAuthorCollection-long-java.lang.String-java.lang.String-}
```
 CommentAuthor(CommentAuthorCollection parentImmediate, long id, String name, String initials)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [CommentAuthorCollection](../../com.aspose.slides/commentauthorcollection) |  |
| id | long |  |
| name | java.lang.String |  |
| initials | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```


Returns or sets the author's name. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Returns or sets the author's name. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public final String getInitials()
```


Returns or sets the authors initials. Read/write String.

**Returns:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public final void setInitials(String value)
```


Returns or sets the authors initials. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final ICommentCollection getComments()
```


Returns the collection of comments made by this author. Read-only [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Returns:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public final void remove()
```


Removes the author from the parent collection.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
