---
title: CellCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một tập hợp các ô.
type: docs
url: /vi/com.aspose.slides/cellcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Biểu diễn một tập hợp các ô.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Trả về số lượng ô trong một tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Trả về một ô theo vị trí của nó. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [getSlide()](#getSlide--) | Trả về slide cha của một CellCollection. |
| [getPresentation()](#getPresentation--) | Trả về presentation cha của một CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị chỉ ra liệu việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ-đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

Trả về số lượng ô trong một tập hợp. Chỉ-đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

Trả về một ô theo vị trí của nó. Chỉ-đọc [Cell](../../com.aspose.slides/cell).

--------------------

Một đối tượng Cell có thể được trả về cho nhiều chỉ số trong trường hợp ô được hợp nhất.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

Trả về một enumerator duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Một IGenericEnumerator có thể được sử dụng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Một java.util.Iterator cho toàn bộ tập hợp.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của một CellCollection. Chỉ-đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về presentation cha của một CellCollection. Chỉ-đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ tập hợp vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị chỉ ra liệu việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. Chỉ-đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Chỉ-đọc Object.

**Trả về:**
java.lang.Object