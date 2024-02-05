---
title: ModernComment
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/moderncomment/
---

## ModernComment class

 Represents a comment on a slide.
 
### getAuthor {#getAuthor}

| Name | Description |
| --- | --- |
| getAuthor () | Returns the author of a comment. Read-only ICommentAuthor. |

 **Result:**
[CommentAuthor](../commentauthor)


---


### getCreatedTime {#getCreatedTime}

| Name | Description |
| --- | --- |
| getCreatedTime () | Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |

 **Result:**
Date


---


### getParentComment {#getParentComment}

| Name | Description |
| --- | --- |
| getParentComment () | Gets or sets parent comment. Read/write IComment. |

 **Result:**
[Comment](../comment), [ModernComment](../moderncomment)

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown when setting the value leads to a circular reference |


---


### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition () | Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |

 **Result:**
Point2D.Float


---


### getShape {#getShape}

| Name | Description |
| --- | --- |
| getShape () | Returns a shape associated with the comment. Read-only IShape. |

 **Result:**
[SummaryZoomSection](../summaryzoomsection), [AutoShape](../autoshape), [AudioFrame](../audioframe), [OleObjectFrame](../oleobjectframe), [SummaryZoomFrame](../summaryzoomframe), [ZoomFrame](../zoomframe), [GraphicalObject](../graphicalobject), [PictureFrame](../pictureframe), [ZoomObject](../zoomobject), [VideoFrame](../videoframe), [GeometryShape](../geometryshape), [SmartArtShape](../smartartshape), [SmartArt](../smartart), [Ink](../ink), [Chart](../chart), [GroupShape](../groupshape), [Table](../table), [SectionZoomFrame](../sectionzoomframe), [Shape](../shape), [LegacyDiagram](../legacydiagram), [Connector](../connector)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns or sets the parent slide of a comment. Read-only ISlide. |

 **Result:**
[Slide](../slide)


---


### getStatus {#getStatus}

| Name | Description |
| --- | --- |
| getStatus () | Gets or sets the status of the comment. Read/write ModernCommentStatus. |

 **Result:**
byte


---


### getText {#getText}

| Name | Description |
| --- | --- |
| getText () | Returns or sets the plain text of a slide comment. Read/write String. |

 **Result:**
String


---


### getTextSelectionLength {#getTextSelectionLength}

| Name | Description |
| --- | --- |
| getTextSelectionLength () | Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int. |

 **Result:**
int


---


### getTextSelectionStart {#getTextSelectionStart}

| Name | Description |
| --- | --- |
| getTextSelectionStart () | Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int. |

 **Result:**
int


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove () | Removes comment and all its replies from the parent collection. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if comment is already removed |


---


### setCreatedTime {#setCreatedTime}

| Name | Description |
| --- | --- |
| setCreatedTime (Date) | Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |


---


### setParentComment {#setParentComment}

| Name | Description |
| --- | --- |
| setParentComment ([Comment](../comment)) | Gets or sets parent comment. Read/write IComment. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown when setting the value leads to a circular reference |


---


### setParentComment {#setParentComment}

| Name | Description |
| --- | --- |
| setParentComment ([ModernComment](../moderncomment)) | Gets or sets parent comment. Read/write IComment. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown when setting the value leads to a circular reference |


---


### setPosition {#setPosition}

| Name | Description |
| --- | --- |
| setPosition (Point2D.Float) | Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |


---


### setStatus {#setStatus}

| Name | Description |
| --- | --- |
| setStatus (byte) | Gets or sets the status of the comment. Read/write ModernCommentStatus. |


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Returns or sets the plain text of a slide comment. Read/write String. |


---


### setTextSelectionLength {#setTextSelectionLength}

| Name | Description |
| --- | --- |
| setTextSelectionLength (int) | Gets or sets text selection length in text frame if the comment associated with AutoShape. Read/write int. |


---


### setTextSelectionStart {#setTextSelectionStart}

| Name | Description |
| --- | --- |
| setTextSelectionStart (int) | Gets or sets starting position of text selection in text frame if the comment associated with AutoShape. Read/write int. |


---


