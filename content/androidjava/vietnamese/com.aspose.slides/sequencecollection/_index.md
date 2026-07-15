---
title: SequenceCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho bộ sưu tập các chuỗi tương tác.
type: docs
url: /vi/com.aspose.slides/sequencecollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Đại diện cho bộ sưu tập các chuỗi tương tác.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCount()](#getCount--) | Trả về số lượng phần tử trong một collection Chỉ đọc int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Thêm chuỗi tương tác mới. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Xóa chuỗi được chỉ định khỏi một collection. |
| [removeAt(int index)](#removeAt-int-) | Xóa chuỗi tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các chuỗi khỏi một collection. |
| [get_Item(int index)](#get-Item-int-) | Trả về một chuỗi tại chỉ mục được chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua collection. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ collection. |
### getCount() {#getCount--}
```
public final int getCount()
```

Trả về số lượng phần tử trong một collection Chỉ đọc int.

**Trả về:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

Thêm chuỗi tương tác mới. Đọc/ghi [Sequence](../../com.aspose.slides/sequence).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Trả về:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

Xóa chuỗi được chỉ định khỏi một collection.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Chuỗi cần xóa. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa chuỗi tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của chuỗi cần được xóa. |
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các chuỗi khỏi một collection.
### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

Trả về một chuỗi tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử. |

**Trả về:**
[ISequence](../../com.aspose.slides/isequence) - Đối tượng [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

Trả về một enumerator cho phép duyệt qua collection.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Một IGenericEnumerator có thể được sử dụng để duyệt qua collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

Trả về một java iterator cho toàn bộ collection.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Một java.util.Iterator cho toàn bộ collection.