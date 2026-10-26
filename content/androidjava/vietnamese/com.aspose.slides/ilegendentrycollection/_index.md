---
title: ILegendEntryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho bộ sưu tập chú giải.
type: docs
url: /vi/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Đại diện cho bộ sưu tập chú giải.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy các thuộc tính của mục chú giải tương ứng với Chart.ChartData.Series[0].DataPoints[index] trong trường hợp kiểu biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; hoặc tương ứng với Chart.ChartData.Series[index] cho các kiểu biểu đồ khác. |
| [getCount()](#getCount--) | Lấy số phần tử thực tế chứa trong bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


Lấy các thuộc tính của mục chú giải tương ứng với Chart.ChartData.Series[0].DataPoints[index] trong trường hợp kiểu biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; hoặc tương ứng với Chart.ChartData.Series[index] cho các kiểu biểu đồ khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Lấy số phần tử thực tế chứa trong bộ sưu tập. int chỉ đọc.

**Giá trị trả về:**
int