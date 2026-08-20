---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: Represents legends collection.
type: docs
url: /vi/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

Đại diện cho bộ sưu tập chú giải.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy thuộc tính của mục chú giải tương ứng với Chart.ChartData.Series[0].DataPoints[index] trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; hoặc tương ứng với Chart.ChartData.Series[index] cho các loại biểu đồ khác. |
| [getCount()](#getCount--) | Lấy số phần tử thực tế có trong bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```


Lấy thuộc tính của mục chú giải tương ứng với Chart.ChartData.Series[0].DataPoints[index] trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; hoặc tương ứng với Chart.ChartData.Series[index] cho các loại biểu đồ khác.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Lấy số phần tử thực tế có trong bộ sưu tập. int chỉ đọc.

**Trả về:**
int