---
title: CommentAuthorCollection
second_title: Tham khảo API Aspose.Slides cho Java
description: Đại diện cho một bộ sưu tập các tác giả bình luận.
type: docs
url: /vi/com.aspose.slides/commentauthorcollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Đại diện cho một bộ sưu tập các tác giả bình luận.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số phần tử thực sự chứa trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Thêm tác giả mới vào cuối bộ sưu tập. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các tác giả. |
| [findByName(String name)](#findByName-java.lang.String-) | Tìm tác giả trong bộ sưu tập theo tên. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Tìm tác giả trong bộ sưu tập theo tên và ký tự đầu. |
| [removeAt(int index)](#removeAt-int-) | Xóa tác giả tại chỉ mục được chỉ định trong bộ sưu tập. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Xóa lần xuất hiện đầu tiên của tác giả được chỉ định trong bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả tác giả khỏi bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### size() {#size--}
```
public final int size()
```


Lấy số phần tử thực sự chứa trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
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
public final ICommentAuthor addAuthor(String name, String initials)
```


Thêm tác giả mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của một tác giả mới. |
| initials | java.lang.String | Tên viết tắt của một tác giả mới. |

**Trả về:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Đối tượng [ICommentAuthor](../../com.aspose.slides/icommentauthor) mới.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```


Tạo và trả về một mảng chứa tất cả các tác giả.

**Trả về:**
com.aspose.slides.ICommentAuthor[] - Mảng của [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
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
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Tìm tác giả trong bộ sưu tập theo tên và ký tự đầu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của tác giả cần tìm. |
| initials | java.lang.String | Ký tự đầu của tác giả cần tìm. |

**Trả về:**
com.aspose.slides.ICommentAuthor[] - Tác giả hoặc null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa tác giả tại chỉ mục được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


Xóa lần xuất hiện đầu tiên của tác giả được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Tác giả cần xóa khỏi bộ sưu tập. |
### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các tác giả khỏi bộ sưu tập.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```


Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**
java.lang.Object