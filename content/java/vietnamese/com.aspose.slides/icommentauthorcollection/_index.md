---
title: ICommentAuthorCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một bộ sưu tập các tác giả bình luận.
type: docs
url: /vi/com.aspose.slides/icommentauthorcollection/
---
**Tất cả các giao diện đã triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Đại diện cho một bộ sưu tập các tác giả bình luận.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Thêm tác giả mới vào cuối bộ sưu tập. |
| [toArray()](#toArray--) | Tạo và trả về một mảng với tất cả các tác giả. |
| [findByName(String name)](#findByName-java.lang.String-) | Tìm tác giả trong bộ sưu tập theo tên. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Tìm tác giả trong bộ sưu tập theo tên và ký tự viết tắt. |
| [removeAt(int index)](#removeAt-int-) | Xóa tác giả tại chỉ mục được chỉ định trong bộ sưu tập. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Xóa lần xuất hiện đầu tiên của tác giả được chỉ định trong bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các tác giả khỏi bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Thêm tác giả mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của tác giả mới. |
| initials | java.lang.String | Ký tự viết tắt của tác giả mới. |

**Trả về:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Đối tượng [ICommentAuthor](../../com.aspose.slides/icommentauthor) mới.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Tạo và trả về một mảng với tất cả các tác giả.

**Trả về:**
com.aspose.slides.ICommentAuthor[] - Mảng của [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Tìm tác giả trong bộ sưu tập theo tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của tác giả cần tìm. |

**Trả về:**
com.aspose.slides.ICommentAuthor[] - Tác giả hoặc null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Tìm tác giả trong bộ sưu tập theo tên và ký tự viết tắt.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của tác giả cần tìm. |
| initials | java.lang.String | Ký tự viết tắt của tác giả cần tìm. |

**Trả về:**
com.aspose.slides.ICommentAuthor[] - Tác giả hoặc null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Xóa tác giả tại chỉ mục được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Xóa lần xuất hiện đầu tiên của tác giả được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Tác giả cần xóa khỏi bộ sưu tập. |

### clear() {#clear--}
```
public abstract void clear()
```


Xóa tất cả các tác giả khỏi bộ sưu tập.