---
title: IPortionCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một bộ sưu tập các phần.
type: docs
url: /vi/com.aspose.slides/iportioncollection/
---
**Tất cả các Interface đã triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Biểu diễn một tập hợp các phần.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [getCount()](#getCount--) | Lấy số lượng phần tử thực sự chứa trong tập hợp. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Thêm một Portion vào cuối tập hợp. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Xác định chỉ mục của một phần cụ thể trong tập hợp. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Chèn một Portion vào tập hợp tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi tập hợp. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục được chỉ định của tập hợp. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định.

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

Lấy số lượng phần tử thực sự chứa trong tập hợp. int chỉ đọc.

**Giá trị trả về:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Thêm một Portion vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion sẽ được thêm vào cuối tập hợp. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Xác định chỉ mục của một phần cụ thể trong tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Phần cần tìm trong tập hợp. |

**Giá trị trả về:**
int - Chỉ mục của item nếu được tìm thấy trong tập hợp; nếu không, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Chèn một Portion vào tập hợp tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số 0 mà Portion sẽ được chèn vào. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion sẽ chèn. |
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi tập hợp.

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
boolean - true nếu item đã được xóa thành công khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection); nếu không, false. Phương thức này cũng trả về false nếu không tìm thấy item trong [IGenericCollection](../../com.aspose.slides/igenericcollection) gốc.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục được chỉ định của tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số 0 của phần tử cần xóa. |