---
title: LegendEntryCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho bộ sưu tập chú giải.
type: docs
url: /vi/com.aspose.slides/legendentrycollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

Đại diện cho bộ sưu tập chú giải.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy các thuộc tính của mục chú giải tương ứng với Chart.ChartData.Series[0].DataPoints[index] trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; hoặc tương ứng với Chart.ChartData.Series[index] cho các loại biểu đồ khác. |
| [getCount()](#getCount--) | Lấy số lượng mục chú giải. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```


Lấy các thuộc tính của mục chú giải tương ứng với Chart.ChartData.Series[0].DataPoints[index] trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; hoặc tương ứng với Chart.ChartData.Series[index] cho các loại biểu đồ khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```


Lấy số lượng mục chú giải. int chỉ đọc.

**Giá trị trả về:**
int