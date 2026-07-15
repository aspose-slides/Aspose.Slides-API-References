---
title: SmartArtNodeCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một bộ sưu tập các nút SmartArt.
type: docs
url: /vi/com.aspose.slides/smartartnodecollection/
---
**Kế thừa:**  
java.lang.Object

**Tất cả các Interface được triển khai:**  
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)  
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Biểu diễn một bộ sưu tập các nút SmartArt.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về nút theo chỉ mục |
| [size()](#size--) | Trả về số lượng nút trong bộ sưu tập Chỉ đọc int Chỉ đọc int |
| [addNode()](#addNode--) | Thêm nút smart art mới hoặc nút con |
| [removeNode(int index)](#removeNode-int-) | Xóa nút hoặc nút con theo chỉ mục |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Xóa nút hoặc nút con |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Thêm nút mới ở vị trí đã chọn trong bộ sưu tập các nút |
| [iterator()](#iterator--) | Trả về một enumerator cho phép lặp qua bộ sưu tập |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ |

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

Trả về số lượng nút trong bộ sưu tập Chỉ đọc int Chỉ đọc int

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

Thêm nút mới ở vị trí đã chọn trong bộ sưu tập các nút

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

Trả về một enumerator cho phép lặp qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Một IGenericEnumerator có thể được sử dụng để lặp qua bộ sưu tập.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Một java.util.Iterator cho toàn bộ bộ sưu tập.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích |
| index | int | Chỉ mục bắt đầu trong mảng đích |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về một giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một gốc đồng bộ. Chỉ đọc Object.

**Trả về:**
java.lang.Object