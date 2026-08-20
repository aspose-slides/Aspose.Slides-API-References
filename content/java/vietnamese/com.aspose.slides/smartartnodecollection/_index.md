---
title: SmartArtNodeCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một tập hợp các nút SmartArt.
type: docs
url: /vi/com.aspose.slides/smartartnodecollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Biểu diễn một tập hợp các nút SmartArt.
## Phương thức

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về nút theo chỉ mục |
| [size()](#size--) | Trả về số lượng nút trong tập hợp Chỉ-đọc  int  Chỉ-đọc  int . |
| [addNode()](#addNode--) | Thêm nút smart art mới hoặc nút con. |
| [removeNode(int index)](#removeNode-int-) | Xóa nút hoặc nút con theo chỉ mục |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Xóa nút hoặc nút con |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Thêm nút mới vào vị trí đã chọn trong tập hợp các nút |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Trả về nút theo chỉ mục

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử |

**Trả về:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nút SmartArt
### size() {#size--}
```
public final int size()
```

Trả về số lượng nút trong tập hợp Chỉ-đọc  int  Chỉ-đọc  int .

**Trả về:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Thêm nút smart art mới hoặc nút con.

**Trả về:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nút đã thêm
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Xóa nút hoặc nút con theo chỉ mục

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của nút |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Xóa nút hoặc nút con

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nút cần xóa |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Thêm nút mới vào vị trí đã chọn trong tập hợp các nút

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Vị trí nút bắt đầu từ 0 |
**Trả về:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nút đã thêm
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Trả về một enumerator cho phép duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Một IGenericEnumerator có thể được sử dụng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Trả về một iterator java cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Một java.util.Iterator cho toàn bộ tập hợp.
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

Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. Chỉ-đọc  boolean .

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một gốc đồng bộ. Chỉ-đọc Object.

**Trả về:**
java.lang.Object