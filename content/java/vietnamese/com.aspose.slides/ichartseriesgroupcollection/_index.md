---
title: IChartSeriesGroupCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho tập hợp các nhóm của các chuỗi có thể kết hợp.
type: docs
url: /vi/com.aspose.slides/ichartseriesgroupcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Đại diện cho tập hợp các nhóm của các chuỗi có thể kết hợp.

--------------------

1) Mỗi nhóm chuỗi chứa các chuỗi có các loại có thể kết hợp. Các nhóm loại chuỗi có thể kết hợp được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup. Ngoài ra, mỗi nhóm chuỗi chứa các chuỗi được vẽ trên trục chính hoặc trên trục phụ (không cả hai trường hợp trong một nhóm). Vì vậy, nguyên tắc nhóm chuỗi là nhóm theo các nhóm loại đã đề cập ở trên và theo kiểu vẽ chính/phụ.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Lấy nhóm chuỗi theo chuỗi. |
| [get_Item(int index)](#get-Item-int-) | Lấy nhóm chuỗi theo chỉ mục. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Lấy nhóm chuỗi theo chuỗi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Giá trị trả về:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Lấy nhóm chuỗi theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)