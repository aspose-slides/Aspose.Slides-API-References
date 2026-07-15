---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn một tác giả của các bình luận.
type: docs
url: /vi/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Biểu diễn một tác giả của các bình luận.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getName()](#getName--) | Trả về hoặc đặt tên của tác giả. |
| [setName(String value)](#setName-java.lang.String-) | Trả về hoặc đặt tên của tác giả. |
| [getInitials()](#getInitials--) | Trả về hoặc đặt ký tự viết tắt của tác giả. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Trả về hoặc đặt ký tự viết tắt của tác giả. |
| [getComments()](#getComments--) | Trả về bộ sưu tập các bình luận do tác giả này tạo. |
| [remove()](#remove--) | Xóa tác giả khỏi bộ sưu tập cha. |
### getName() {#getName--}
```
public abstract String getName()
```

Trả về hoặc đặt tên của tác giả. Đọc/ghi String.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Trả về hoặc đặt tên của tác giả. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

Trả về hoặc đặt ký tự viết tắt của tác giả. Đọc/ghi String.

**Trả về:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Trả về hoặc đặt ký tự viết tắt của tác giả. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Trả về bộ sưu tập các bình luận do tác giả này tạo. Chỉ đọc [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Trả về:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

Xóa tác giả khỏi bộ sưu tập cha.