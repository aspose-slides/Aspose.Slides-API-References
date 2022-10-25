---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: Represents an author of comments.
type: docs
weight: 724
url: /java/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Represents an author of comments.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns or sets the author's name. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the author's name. |
| [getInitials()](#getInitials--) | Returns or sets the authors initials. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Returns or sets the authors initials. |
| [getComments()](#getComments--) | Returns the collection of comments made by this author. |
| [remove()](#remove--) | Removes the author from the parent collection. |
### getName() {#getName--}
```
public abstract String getName()
```


Returns or sets the author's name. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Returns or sets the author's name. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Returns or sets the authors initials. Read/write String.

**Returns:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Returns or sets the authors initials. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Returns the collection of comments made by this author. Read-only [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Returns:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Removes the author from the parent collection.

