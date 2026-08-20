---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: Represents a comment on a slide.
type: docs
url: /vi/com.aspose.slides/icomment/
---```
public interface IComment
```

Biểu diễn một bình luận trên slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getText()](#getText--) | Trả về hoặc đặt văn bản thuần của một bình luận trên slide. |
| [setText(String value)](#setText-java.lang.String-) | Trả về hoặc đặt văn bản thuần của một bình luận trên slide. |
| [getCreatedTime()](#getCreatedTime--) | Trả về hoặc đặt thời gian tạo bình luận. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Trả về hoặc đặt thời gian tạo bình luận. |
| [getSlide()](#getSlide--) | Trả về hoặc đặt slide cha của một bình luận. |
| [getAuthor()](#getAuthor--) | Trả về tác giả của một bình luận. |
| [getPosition()](#getPosition--) | Trả về hoặc đặt vị trí của một bình luận trên slide. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Trả về hoặc đặt vị trí của một bình luận trên slide. |
| [remove()](#remove--) | Xóa bình luận và tất cả các phản hồi của nó khỏi bộ sưu tập cha. |
| [getParentComment()](#getParentComment--) | Lấy hoặc đặt bình luận cha. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Lấy hoặc đặt bình luận cha. |
### getText() {#getText--}
```
public abstract String getText()
```


Trả về hoặc đặt văn bản thuần của một bình luận trên slide. Đọc/ghi String.

**Trả về:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Trả về hoặc đặt văn bản thuần của một bình luận trên slide. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Trả về hoặc đặt thời gian tạo bình luận. Đặt thuộc tính này thành java.util.Date(Long.MIN\_VALUE) có nghĩa là không có thời gian bình luận nào được đặt. Đọc/ghi java.util.Date.

--------------------

Thời gian bình luận là một tham số tùy chọn.

**Trả về:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Trả về hoặc đặt thời gian tạo bình luận. Đặt thuộc tính này thành java.util.Date(Long.MIN\_VALUE) có nghĩa là không có thời gian bình luận nào được đặt. Đọc/ghi java.util.Date.

--------------------

Thời gian bình luận là một tham số tùy chọn.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


Trả về hoặc đặt slide cha của một bình luận. Chỉ đọc [ISlide](../../com.aspose.slides/islide).

**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


Trả về tác giả của một bình luận. Chỉ đọc [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Trả về:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```


Trả về hoặc đặt vị trí của một bình luận trên slide. Đọc/ghi java.awt.geom.Point2D.Float.

**Trả về:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```


Trả về hoặc đặt vị trí của một bình luận trên slide. Đọc/ghi java.awt.geom.Point2D.Float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public abstract void remove()
```


Xóa bình luận và tất cả các phản hồi của nó khỏi bộ sưu tập cha.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


Lấy hoặc đặt bình luận cha. Đọc/ghi [IComment](../../com.aspose.slides/icomment).

**Trả về:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


Lấy hoặc đặt bình luận cha. Đọc/ghi [IComment](../../com.aspose.slides/icomment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |