---
title: Comment
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/comment/
---

## Comment class

 Represents a comment on a slide.
 
### getAuthor {#getAuthor}

| Name | Description |
| --- | --- |
| getAuthor () | Returns the author of a comment. Read-only ICommentAuthor. |

 **Returns:**
[CommentAuthor](../commentauthor)


---


### getCreatedTime {#getCreatedTime}

| Name | Description |
| --- | --- |
| getCreatedTime () | Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |

 **Returns:**
Date


---


### getParentComment {#getParentComment}

| Name | Description |
| --- | --- |
| getParentComment () | Gets or sets parent comment. Read/write IComment. |

 **Returns:**
[Comment](../comment), [ModernComment](../moderncomment)

 **Exception**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown when setting the value leads to a circular reference |


---


### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition () | Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |

 **Returns:**
Point2D.Float


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns or sets the parent slide of a comment. Read-only ISlide. |

 **Returns:**
[Slide](../slide)


---


### getText {#getText}

| Name | Description |
| --- | --- |
| getText () | Returns or sets the plain text of a slide comment. Read/write String. |

 **Returns:**
String


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | Removes comment and all its replies from the parent collection. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if comment is already removed |


---


### setCreatedTime {#setCreatedTime}

| Name | Description |
| --- | --- |
| setCreatedTime (Date) | Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |

 **Returns:**
void


---


### setParentComment {#setParentComment}

| Name | Description |
| --- | --- |
| setParentComment ([Comment](../comment)) | Gets or sets parent comment. Read/write IComment. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown when setting the value leads to a circular reference |


---


### setParentComment {#setParentComment}

| Name | Description |
| --- | --- |
| setParentComment ([ModernComment](../moderncomment)) | Gets or sets parent comment. Read/write IComment. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown when setting the value leads to a circular reference |


---


### setPosition {#setPosition}

| Name | Description |
| --- | --- |
| setPosition (Point2D.Float) | Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |

 **Returns:**
void


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Returns or sets the plain text of a slide comment. Read/write String. |

 **Returns:**
void


---


