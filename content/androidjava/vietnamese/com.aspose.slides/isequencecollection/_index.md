---
title: ISequenceCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho bộ sưu tập các chuỗi tương tác.
type: docs
url: /vi/com.aspose.slides/isequencecollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Đại diện cho bộ sưu tập các chuỗi tương tác.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCount()](#getCount--) | Trả về số phần tử trong một bộ sưu tập chỉ đọc int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Thêm chuỗi tương tác mới. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Xóa chuỗi đã chỉ định khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa chuỗi tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các chuỗi khỏi bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về một chuỗi tại chỉ mục được chỉ định. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Trả về số phần tử trong một bộ sưu tập chỉ đọc int.

**Trả về:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


Thêm chuỗi tương tác mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Đối tượng Shape [IShape](../../com.aspose.slides/ishape) |

**Trả về:**
[ISequence](../../com.aspose.slides/isequence) - Chuỗi mới [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


Xóa chuỗi đã chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Chuỗi để xóa. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Xóa chuỗi tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử trong bộ sưu tập int |

### clear() {#clear--}
```
public abstract void clear()
```


Xóa tất cả các chuỗi khỏi bộ sưu tập.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


Trả về một chuỗi tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử. |

**Trả về:**
[ISequence](../../com.aspose.slides/isequence) - Đối tượng [ISequence](../../com.aspose.slides/isequence).