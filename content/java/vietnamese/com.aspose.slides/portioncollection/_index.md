---
title: PortionCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bộ sưu tập các phần.
type: docs
url: /vi/com.aspose.slides/portioncollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Biểu diễn một bộ sưu tập các phần.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCount()](#getCount--) | Lấy số lượng phần tử thực tế có trong bộ sưu tập. |
| [isReadOnly()](#isReadOnly--) | Lấy giá trị cho biết liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có chỉ đọc hay không. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Thêm một Portion vào cuối bộ sưu tập. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Xác định chỉ mục của một mục cụ thể trong List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Chèn một Portion vào bộ sưu tập tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một Mảng, bắt đầu tại một chỉ mục Mảng nhất định. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục được chỉ định của bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
### getCount() {#getCount--}
```
public final int getCount()
```

Lấy số lượng phần tử thực tế có trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Lấy giá trị cho biết liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có chỉ đọc hay không. Chỉ đọc boolean.

**Trả về:**
boolean - true nếu [IGenericCollection](../../com.aspose.slides/igenericcollection) là chỉ đọc; ngược lại, false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

Lấy phần tử tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Thêm một Portion vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion sẽ được thêm vào cuối bộ sưu tập. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Xác định chỉ mục của một mục cụ thể trong List.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Đối tượng cần tìm trong List. |

**Trả về:**
int - Chỉ mục của mục nếu tìm thấy trong danh sách; nếu không, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Chèn một Portion vào bộ sưu tập tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 tại đó Portion sẽ được chèn. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion sẽ chèn. |
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Đối tượng cần tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu mục được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection); nếu không, false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một Mảng, bắt đầu tại một chỉ mục Mảng nhất định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Mảng một chiều là nơi chứa các phần tử được sao chép từ [IGenericCollection](../../com.aspose.slides/igenericcollection). Mảng phải có chỉ mục bắt đầu từ 0. |
| arrayIndex | int | Chỉ mục bắt đầu từ 0 trong mảng mà việc sao chép bắt đầu. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Đối tượng cần xóa khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu mục đã được xóa thành công khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection); nếu không, false. Phương thức này cũng trả về false nếu mục không được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection) gốc.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phần tử tại chỉ mục được chỉ định của bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Một java.util.Iterator cho toàn bộ bộ sưu tập.