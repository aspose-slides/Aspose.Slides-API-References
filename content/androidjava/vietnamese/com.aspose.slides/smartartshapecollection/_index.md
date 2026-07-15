---
title: SmartArtShapeCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu thị một bộ sưu tập các hình SmartArt
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

Biểu thị một bộ sưu tập các hình SmartArt
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số phần tử thực sự có trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ số đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator để duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
### size() {#size--}
```
public final int size()
```

Lấy số phần tử thực sự có trong bộ sưu tập. Chỉ đọc int.

**Trả về:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

Lấy phần tử tại chỉ số đã chỉ định. Chỉ đọc [SmartArtShape](../../com.aspose.slides/smartartshape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của hình dạng |

**Trả về:**  
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - Hình SmartArt
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với đa luồng) hay không. Chỉ đọc boolean.

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

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ số bắt đầu trong mảng đích. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

Trả về một enumerator để duyệt qua bộ sưu tập.

**Trả về:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Một java.util.Iterator cho toàn bộ bộ sưu tập.