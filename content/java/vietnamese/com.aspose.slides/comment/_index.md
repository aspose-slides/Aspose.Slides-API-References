---
title: Comment
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bình luận trên slide.
type: docs
url: /vi/com.aspose.slides/comment/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Biểu diễn một bình luận trên slide.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Khởi tạo lớp Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Thêm một slide trống
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Thêm một tác giả
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Đặt vị trí cho các bình luận
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Thêm bình luận slide cho tác giả trên slide 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Thêm bình luận slide cho tác giả trên slide 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Lưu tệp PowerPoint Presentation
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Khởi tạo lớp Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Lặp qua các CommentAuthor
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Lặp qua các bình luận
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
>  // Khởi tạo lớp Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Thêm một bình luận
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // Thêm một trả lời cho comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Thêm một trả lời khác cho comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Thêm một trả lời cho câu trả lời hiện có
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Hiển thị cấu trúc cây bình luận trên console
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
>      // Xóa comment1 và tất cả các trả lời của nó
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getText()](#getText--) | Trả về hoặc đặt văn bản thường của một bình luận trên slide. |
| [setText(String value)](#setText-java.lang.String-) | Trả về hoặc đặt văn bản thường của một bình luận trên slide. |
| [getCreatedTime()](#getCreatedTime--) | Trả về hoặc đặt thời gian tạo bình luận. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Trả về hoặc đặt thời gian tạo bình luận. |
| [getSlide()](#getSlide--) | Trả về hoặc đặt slide cha của một bình luận. |
| [getAuthor()](#getAuthor--) | Trả về tác giả của một bình luận. |
| [getPosition()](#getPosition--) | Trả về hoặc đặt vị trí của một bình luận trên slide. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Trả về hoặc đặt vị trí của một bình luận trên slide. |
| [remove()](#remove--) | Xóa bình luận và tất cả các phản hồi của nó khỏi bộ sưu tập cha. |
| [getParentComment()](#getParentComment--) | Lấy hoặc đặt bình luận cha. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Lấy hoặc đặt bình luận cha. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

Trả về hoặc đặt văn bản thường của một bình luận trên slide. Đọc/ghi String.

**Trả về:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Trả về hoặc đặt văn bản thường của một bình luận trên slide. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Trả về hoặc đặt thời gian tạo bình luận. Đặt thuộc tính này thành java.util.Date(Long.MIN\_VALUE) có nghĩa là không có thời gian bình luận được đặt. Đọc/ghi java.util.Date.

--------------------

Thời gian bình luận là một tham số tùy chọn.

**Trả về:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Trả về hoặc đặt thời gian tạo bình luận. Đặt thuộc tính này thành java.util.Date(Long.MIN\_VALUE) có nghĩa là không có thời gian bình luận được đặt. Đọc/ghi java.util.Date.

--------------------

Thời gian bình luận là một tham số tùy chọn.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Trả về hoặc đặt slide cha của một bình luận. Chỉ đọc [ISlide](../../com.aspose.slides/islide).

**Trả về:**
[ISlide](../../com.aspose.slides/islide)

### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Trả về tác giả của một bình luận. Chỉ đọc [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Trả về:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

Trả về hoặc đặt vị trí của một bình luận trên slide. Đọc/ghi java.awt.geom.Point2D.Float.

**Trả về:**
java.awt.geom.Point2D.Float

### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

Trả về hoặc đặt vị trí của một bình luận trên slide. Đọc/ghi java.awt.geom.Point2D.Float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```

Xóa bình luận và tất cả các phản hồi của nó khỏi bộ sưu tập cha.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Lấy hoặc đặt bình luận cha. Đọc/ghi [IComment](../../com.aspose.slides/icomment).

**Trả về:**
[IComment](../../com.aspose.slides/icomment)

### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Lấy hoặc đặt bình luận cha. Đọc/ghi [IComment](../../com.aspose.slides/icomment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject