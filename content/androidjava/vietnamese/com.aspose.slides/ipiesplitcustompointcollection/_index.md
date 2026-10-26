---
title: IPieSplitCustomPointCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Mô tả một tập hợp các điểm sẽ được vẽ trong phần bánh hoặc thanh thứ hai trên biểu đồ thanh-của-bánh hoặc bánh-của-bánh với phân tách tùy chỉnh.
type: docs
url: /vi/com.aspose.slides/ipiesplitcustompointcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Mô tả một tập hợp các điểm sẽ được vẽ trong phần bánh hoặc thanh thứ hai trên biểu đồ thanh-của-bánh hoặc bánh-của-bánh với phân tách tùy chỉnh.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về điểm dữ liệu biểu đồ theo chỉ mục. |
| [add(int dataPointIndex)](#add-int-) | Thêm điểm dữ liệu theo chỉ mục của nó trong bộ sưu tập điểm của chuỗi cha. |
| [remove(int dataPointIndex)](#remove-int-) | Xóa mục khỏi tập hợp theo chỉ mục của nó trong bộ sưu tập điểm của chuỗi cha. |
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

Thêm điểm dữ liệu theo chỉ mục của nó trong bộ sưu tập điểm của chuỗi cha.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| dataPointIndex | int | Chỉ mục của điểm dữ liệu trong bộ sưu tập điểm của chuỗi cha. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Xóa mục khỏi tập hợp theo chỉ mục của nó trong bộ sưu tập điểm của chuỗi cha.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| dataPointIndex | int | Chỉ mục của điểm dữ liệu trong bộ sưu tập điểm của chuỗi cha.. |