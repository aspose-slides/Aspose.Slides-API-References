---
title: Comment
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/comment/
---

## Comment class

 Represents a comment on a slide.
 
| [getAuthor] () Returns the author of a comment. Read-only ICommentAuthor. |

### Result
[CommentAuthor]


---


| [getCreatedTime] () Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |

### Result
Date


---


| [getParentComment] () Gets or sets parent comment. Read/write IComment. |

### Result
[Comment], [ModernComment]

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown when setting the value leads to a circular reference |


---


| [getPosition] () Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |

### Result
Point2D.Float


---


| [getSlide] () Returns or sets the parent slide of a comment. Read-only ISlide. |

### Result
[Slide]


---


| [getText] () Returns or sets the plain text of a slide comment. Read/write String. |

### Result
String


---


| [remove] () Removes comment and all its replies from the parent collection. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if comment is already removed |


---


| [setCreatedTime] ([Date]) Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |


---


| [setParentComment] ([Comment]) Gets or sets parent comment. Read/write IComment. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown when setting the value leads to a circular reference |


---


| [setParentComment] ([ModernComment]) Gets or sets parent comment. Read/write IComment. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown when setting the value leads to a circular reference |


---


| [setPosition] ([Point2D.Float]) Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |


---


| [setText] ([String]) Returns or sets the plain text of a slide comment. Read/write String. |


---


