---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides cho Java - Tham chiếu API
description: Biểu diễn một tập hợp các điểm sẽ được vẽ trong phần trăm hoặc thanh thứ hai trên biểu đồ bar-of-pie hoặc pie-of-pie với phân tách tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/ipiesplitcustompointcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Biểu diễn một tập hợp các điểm sẽ được vẽ trong phần trăm hoặc thanh thứ hai trên biểu đồ bar-of-pie hoặc pie-of-pie với phần tách tùy chỉnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về điểm dữ liệu biểu đồ theo chỉ mục. |
| [add(int dataPointIndex)](#add-int-) | Thêm điểm dữ liệu theo chỉ mục của nó trong bộ sưu tập các điểm của chuỗi cha. |
| [remove(int dataPointIndex)](#remove-int-) | Xóa mục khỏi bộ sưu tập theo chỉ mục của nó trong bộ sưu tập các điểm của chuỗi cha. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Trả về điểm dữ liệu biểu đồ theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu biểu đồ.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Thêm điểm dữ liệu theo chỉ mục của nó trong bộ sưu tập các điểm của chuỗi cha.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| dataPointIndex | int | Chỉ mục của điểm dữ liệu trong bộ sưu tập các điểm của chuỗi cha. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Xóa mục khỏi bộ sưu tập theo chỉ mục của nó trong bộ sưu tập các điểm của chuỗi cha.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| dataPointIndex | int | Chỉ mục của điểm dữ liệu trong bộ sưu tập các điểm của chuỗi cha.. |