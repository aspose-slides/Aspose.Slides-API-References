---  
title: IPortionCollection  
second_title: Tham chiếu API Aspose.Slides cho Java  
description: Biểu thị một bộ sưu tập các Portion.  
type: docs  
url: /vi/com.aspose.slides/iportioncollection/  
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Biểu thị một bộ sưu tập các Portion.
## Phương thức

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [getCount()](#getCount--) | Lấy số lượng phần tử thực tế chứa trong bộ sưu tập. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Thêm một Portion vào cuối bộ sưu tập. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Xác định chỉ mục của một Portion cụ thể trong bộ sưu tập. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Chèn một Portion vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định của bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số lượng phần tử thực tế chứa trong bộ sưu tập. int chỉ đọc.

**Giá trị trả về:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Thêm một Portion vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion sẽ được thêm vào cuối bộ sưu tập. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Xác định chỉ mục của một Portion cụ thể trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Phần cần tìm trong bộ sưu tập. |

**Giá trị trả về:**
int - Chỉ mục của mục nếu tìm thấy trong bộ sưu tập; nếu không, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Chèn một Portion vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số 0 mà Portion sẽ được chèn vào. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion cần chèn. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Đối tượng cần tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Giá trị trả về:**
boolean - true nếu item được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection); nếu không, false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Đối tượng cần xóa khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Giá trị trả về:**
boolean - true nếu item đã được xóa thành công khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection); nếu không, false. Phương thức này cũng trả về false nếu không tìm thấy item trong [IGenericCollection](../../com.aspose.slides/igenericcollection) ban đầu.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định của bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số 0 của phần tử cần xóa. |