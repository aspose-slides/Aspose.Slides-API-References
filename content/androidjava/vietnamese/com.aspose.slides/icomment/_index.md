---
title: IComment
second_title: Tài liệu API Java cho Aspose.Slides cho Android
description: Biểu diễn một bình luận trên slide.
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
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Trả về hoặc đặt vị trí của một bình luận trên slide. |
| [remove()](#remove--) | Xóa bình luận và tất cả các trả lời của nó khỏi bộ sưu tập cha. |
| [getParentComment()](#getParentComment--) | Lấy hoặc đặt bình luận cha. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Lấy hoặc đặt bình luận cha. |
### getText() {#getText--}
```
public abstract String getText()
```

Trả về hoặc đặt văn bản thuần của một bình luận trên slide. Đọc/ghi String.

**Giá trị trả về:**
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

Trả về hoặc đặt thời gian tạo bình luận. Đặt thuộc tính này thành java.util.Date(Long.MIN_VALUE) có nghĩa là không có thời gian bình luận nào được đặt. Đọc/ghi java.util.Date.

--------------------

Thời gian bình luận là một tham số tùy chọn.

**Giá trị trả về:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Trả về hoặc đặt thời gian tạo bình luận. Đặt thuộc tính này thành java.util.Date(Long.MIN_VALUE) có nghĩa là không có thời gian bình luận nào được đặt. Đọc/ghi java.util.Date.

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

**Giá trị trả về:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Trả về tác giả của một bình luận. Chỉ đọc [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Giá trị trả về:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Trả về hoặc đặt vị trí của một bình luận trên slide. Đọc/ghi android.graphics.PointF.

**Giá trị trả về:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Trả về hoặc đặt vị trí của một bình luận trên slide. Đọc/ghi android.graphics.PointF.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

Xóa bình luận và tất cả các trả lời của nó khỏi bộ sưu tập cha.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Lấy hoặc đặt bình luận cha. Đọc/ghi [IComment](../../com.aspose.slides/icomment).

**Giá trị trả về:**
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