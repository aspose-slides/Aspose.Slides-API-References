---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một tập hợp các điểm để tách điểm trong biểu đồ bar-of-pie hoặc pie-of-pie với tách tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/piesplitcustompointcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Đại diện cho một tập hợp các điểm để tách điểm trong biểu đồ bar-of-pie hoặc pie-of-pie có tách tùy chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về điểm dữ liệu biểu đồ cho chỉ mục đã chỉ định. |
| [add(int dataPointIndex)](#add-int-) | Thêm điểm dữ liệu theo chỉ mục của nó trong bộ sưu tập điểm của chuỗi cha. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Thêm điểm dữ liệu vào bộ sưu tập. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Xóa mục khỏi bộ sưu tập. |
| [remove(int dataPointIndex)](#remove-int-) | Xóa mục khỏi bộ sưu tập theo chỉ mục của nó trong bộ sưu tập điểm của chuỗi cha. |
| [clear()](#clear--) | Xóa tất cả các mục khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một mảng, bắt đầu tại một chỉ mục mảng cụ thể. |
| [size()](#size--) | Trả về hoặc đặt số lượng điểm dữ liệu biểu đồ. |
| [isReadOnly()](#isReadOnly--) | Lấy giá trị cho biết liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có ở chế độ chỉ đọc hay không. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ hoá. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Trả về điểm dữ liệu biểu đồ cho chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục. |

**Trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu biểu đồ.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Thêm điểm dữ liệu theo chỉ mục của nó trong bộ sưu tập điểm của chuỗi cha.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| dataPointIndex | int | Chỉ mục của điểm dữ liệu trong bộ sưu tập điểm của chuỗi cha. |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Thêm điểm dữ liệu vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Điểm dữ liệu để thêm vào. |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Xóa mục khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Điểm dữ liệu để xóa. |

**Trả về:**
boolean - true nếu mục được xóa thành công; ngược lại, false. Phương thức này cũng trả về false nếu không tìm thấy mục trong System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Xóa mục khỏi bộ sưu tập theo chỉ mục của nó trong bộ sưu tập điểm của chuỗi cha.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| dataPointIndex | int | Chỉ mục của điểm dữ liệu trong bộ sưu tập điểm của chuỗi cha. |
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các mục khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection).
### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Đối tượng cần tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu mục được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection); ngược lại, false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một mảng, bắt đầu tại một chỉ mục mảng cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Mảng một chiều là đích đến của các phần tử được sao chép từ [IGenericCollection](../../com.aspose.slides/igenericcollection). Mảng phải có chỉ mục bắt đầu từ 0. |
| arrayIndex | int | Chỉ mục bắt đầu sao chép trong mảng (bắt đầu từ 0). |
### size() {#size--}
```
public final int size()
```

Trả về hoặc đặt số lượng điểm dữ liệu biểu đồ. int chỉ đọc.

**Trả về:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Lấy giá trị cho biết liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có ở chế độ chỉ đọc hay không. boolean chỉ đọc.

**Trả về:**
boolean - true nếu [IGenericCollection](../../com.aspose.slides/igenericcollection) ở chế độ chỉ đọc; ngược lại, false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. boolean chỉ đọc.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về gốc đồng bộ hoá. Object chỉ đọc.

**Trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Một IGenericEnumerator có thể được dùng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Trả về một iterator java cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Một java.util.Iterator cho toàn bộ bộ sưu tập.