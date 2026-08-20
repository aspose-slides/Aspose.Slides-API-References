---
title: LayoutSlideCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho lớp cơ sở cho bộ sưu tập các slide bố cục.
type: docs
url: /vi/com.aspose.slides/layoutslidecollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Đại diện cho lớp cơ sở cho bộ sưu tập các slide bố cục.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng slide bố cục trong một bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về slide bố cục theo chỉ mục. |
| [getByType(byte type)](#getByType-byte-) | Trả về slide bố cục đầu tiên của loại được chỉ định. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Xóa một bố cục khỏi bộ sưu tập. |
| [removeUnused()](#removeUnused--) | Xóa các slide bố cục không được sử dụng (các slide bố cục mà HasDependingSlides là false). |
| [iterator()](#iterator--) | Trả về một enumerator để lặp qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có đồng bộ (an toàn với luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Trả về số lượng slide bố cục trong một bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Trả về slide bố cục theo chỉ mục. Chỉ đọc [LayoutSlide](../../com.aspose.slides/layoutslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

Trả về slide bố cục đầu tiên của loại được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | byte | Một loại slide bố cục để tìm. |

**Trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) với loại được chỉ định hoặc null nếu không tìm thấy bố cục.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Xóa một bố cục khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide bố cục cần xóa khỏi bộ sưu tập.

--------------------

1) Để tránh việc ném PptxEditException, kiểm tra thuộc tính HasDependingSlides của bố cục trước. 2) Bạn cũng có thể sử dụng phương thức [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) để đơn giản hoá mã. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Xóa các slide bố cục không được sử dụng (các slide bố cục mà HasDependingSlides là false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Trả về một enumerator để lặp qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Một IGenericEnumerator có thể được sử dụng để lặp qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào bộ sưu tập có đồng bộ (an toàn với luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject