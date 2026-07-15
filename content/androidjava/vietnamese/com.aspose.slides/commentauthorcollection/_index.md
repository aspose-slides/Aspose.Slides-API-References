---
title: CommentAuthorCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một tập hợp các tác giả bình luận.
type: docs
url: /vi/com.aspose.slides/commentauthorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Biểu diễn một tập hợp các tác giả bình luận.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số phần tử thực sự chứa trong tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Thêm tác giả mới vào cuối tập hợp. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả các tác giả. |
| [findByName(String name)](#findByName-java.lang.String-) | Tìm tác giả trong tập hợp theo tên. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Tìm tác giả trong tập hợp theo tên và ký hiệu. |
| [removeAt(int index)](#removeAt-int-) | Xóa tác giả tại chỉ mục được chỉ định trong tập hợp. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Xóa lần xuất hiện đầu tiên của tác giả được chỉ định trong tập hợp. |
| [clear()](#clear--) | Xóa tất cả các tác giả khỏi tập hợp. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp sang mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### size() {#size--}
```
public final int size()
```

Lấy số phần tử thực sự chứa trong tập hợp. Chỉ đọc int.

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

Thêm tác giả mới vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của tác giả mới. |
| initials | java.lang.String | Ký hiệu của tác giả mới. |

**Trả về:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - New [ICommentAuthor](../../com.aspose.slides/icommentauthor) object.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Tạo và trả về một mảng chứa tất cả các tác giả.

**Trả về:**
com.aspose.slides.ICommentAuthor[] - Array of [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Tìm tác giả trong tập hợp theo tên.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của tác giả cần tìm. |

**Trả về:**
com.aspose.slides.ICommentAuthor[] - Author or null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Tìm tác giả trong tập hợp theo tên và ký hiệu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của tác giả cần tìm. |
| initials | java.lang.String | Ký hiệu của tác giả cần tìm. |

**Trả về:**
com.aspose.slides.ICommentAuthor[] - Author or null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa tác giả tại chỉ mục được chỉ định trong tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục không dựa trên 0 của phần tử cần xóa. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Xóa lần xuất hiện đầu tiên của tác giả được chỉ định trong tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Tác giả cần xóa khỏi tập hợp. |
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các tác giả khỏi tập hợp.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Trả về một enumerator duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ tập hợp sang mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**
java.lang.Object