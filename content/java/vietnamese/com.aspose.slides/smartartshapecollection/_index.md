---
title: SmartArtShapeCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một tập hợp các hình SmartArt
type: docs
url: /vi/com.aspose.slides/smartartshapecollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

Đại diện cho một tập hợp các hình SmartArt
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số lượng phần tử thực sự chứa trong tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (an toàn với luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp vào mảng được chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator để duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ tập hợp. |
### size() {#size--}
```
public final int size()
```


Lấy số lượng phần tử thực sự chứa trong tập hợp. Chỉ đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```


Lấy phần tử tại chỉ mục đã chỉ định. Chỉ đọc [SmartArtShape](../../com.aspose.slides/smartartshape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hình |

**Trả về:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - Hình SmartArt
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (an toàn với luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về gốc đồng bộ. Chỉ đọc Object.

**Trả về:**
java.lang.Object
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

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```


Trả về một enumerator để duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Một IGenericEnumerator có thể được dùng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```


Trả về một iterator java cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Một java.util.Iterator cho toàn bộ tập hợp.