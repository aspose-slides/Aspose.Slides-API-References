---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: Represents an author of comments.
type: docs
url: /vi/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Biểu diễn một tác giả của các bình luận.

## Phương thức

| Method | Mô tả |
| --- | --- |
| [getName()](#getName--) | Trả về hoặc đặt tên của tác giả. |
| [setName(String value)](#setName-java.lang.String-) | Trả về hoặc đặt tên của tác giả. |
| [getInitials()](#getInitials--) | Trả về hoặc đặt chữ viết tắt của tác giả. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Trả về hoặc đặt chữ viết tắt của tác giả. |
| [getComments()](#getComments--) | Trả về tập hợp các bình luận được tạo bởi tác giả này. |
| [remove()](#remove--) | Xóa tác giả khỏi tập hợp cha. |

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

Trả về hoặc đặt chữ viết tắt của tác giả. Đọc/ghi String.

**Trả về:**
java.lang.String

### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Trả về hoặc đặt chữ viết tắt của tác giả. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Trả về tập hợp các bình luận được tạo bởi tác giả này. Chỉ đọc [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Trả về:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)

### remove() {#remove--}
```
public abstract void remove()
```

Xóa tác giả khỏi tập hợp cha.