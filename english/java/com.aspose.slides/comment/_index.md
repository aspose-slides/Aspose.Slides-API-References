---
title: Comment
second_title: Aspose.Slides for Java API Reference
description: Represents a comment on a slide.
type: docs
weight: 126
url: /java/com.aspose.slides/comment/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Represents a comment on a slide.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Instantiates the Presentation class
>  Presentation presentation = new Presentation();
>  try {
>     // Adds an empty slide
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Adds an author
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Sets the position for comments
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Adds slide comment for an author on slide 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Adds slide comment for an author on slide 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Save the PowerPoint Presentation file
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Instantiates the Presentation class
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Iterate CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Iterate Comments
>          for (IComment comment1 : author.getComments())
>          {
>              Comment comment = (Comment) comment1;
>              System.out.println("ISlide :" + comment.getSlide().getSlideNumber() + " has comment: " + comment.getText() + " with Author: " + comment.getAuthor().getName() + " posted on time :" + comment.getCreatedTime().toString() + "\n");
>          }
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to add comments and get replies to them.
>  
>  // Instantiates the Presentation class
>  Presentation pres = new Presentation();
>  try {
>     // Adds a comment
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // Adds a reply to comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Adds another reply to comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Adds a reply to existing reply
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Displays the comments hierarchy on console
>      ISlide slide = pres.getSlides().get_Item(0);
>      IComment[] comments = slide.getSlideComments(null);
>      for (int i = 0; i < comments.length; i++)
>      {
>          IComment comment = comments[i];
>          while (comment.getParentComment() != null)
>          {
>              System.out.println("\t");
>              comment = comment.getParentComment();
>          }
>          System.out.println(comments[i].getAuthor().getName() + " : " + comments[i].getText());
>      }
>      pres.save("parent_comment.pptx",SaveFormat.Pptx);
>      // Removes comment1 and all replies to it
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Returns or sets the plain text of a slide comment. |
| [setText(String value)](#setText-java.lang.String-) | Returns or sets the plain text of a slide comment. |
| [getCreatedTime()](#getCreatedTime--) | Returns or sets the time of a comment creation. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returns or sets the time of a comment creation. |
| [getSlide()](#getSlide--) | Returns or sets the parent slide of a comment. |
| [getAuthor()](#getAuthor--) | Returns the author of a comment. |
| [getPosition()](#getPosition--) | Returns or sets the position of a comment on a slide. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Returns or sets the position of a comment on a slide. |
| [remove()](#remove--) | Removes comment and all its replies from the parent collection. |
| [getParentComment()](#getParentComment--) | Gets or sets parent comment. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Gets or sets parent comment. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```


Returns or sets the plain text of a slide comment. Read/write String.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Returns or sets the plain text of a slide comment. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN\_VALUE) means no comment time is set. Read/write java.util.Date.

--------------------

Comment time is an optional parameter.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN\_VALUE) means no comment time is set. Read/write java.util.Date.

--------------------

Comment time is an optional parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```


Returns or sets the parent slide of a comment. Read-only [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```


Returns the author of a comment. Read-only [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returns:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```


Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float.

**Returns:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```


Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```


Removes comment and all its replies from the parent collection.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```


Gets or sets parent comment. Read/write [IComment](../../com.aspose.slides/icomment).

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```


Gets or sets parent comment. Read/write [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
