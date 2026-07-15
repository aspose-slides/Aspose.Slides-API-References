---
title: CellCollection
second_title: Aspose.Slides cho Android qua Java API Reference
description: Biểu diễn một bộ sưu tập các ô.
type: docs
url: /vi/com.aspose.slides/cellcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được triển khai:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Biểu diễn một bộ sưu tập các ô.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Trả về số lượng ô trong một bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về một ô theo vị trí của nó. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [getSlide()](#getSlide--) | Trả về slide cha của một CellCollection. |
| [getPresentation()](#getPresentation--) | Trả về bản trình chiếu cha của một CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một root đồng bộ hoá. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent\_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```


Trả về số lượng ô trong một bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```


Trả về một ô theo vị trí của nó. Chỉ đọc [Cell](../../com.aspose.slides/cell).

--------------------

Một đối tượng Cell có thể được trả về cho nhiều chỉ mục trong trường hợp ô được hợp nhất.

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


Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```


Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - An java.util.Iterator for the entire collection.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Trả về slide cha của một CellCollection. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Trả về bản trình chiếu cha của một CellCollection. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)
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


Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một root đồng bộ hoá. Chỉ đọc Object.

**Trả về:**
java.lang.Object