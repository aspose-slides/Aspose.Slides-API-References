---
title: IChartSeriesGroupCollection
second_title: Tham khảo API Java của Aspose.Slides cho Android
description: Đại diện cho tập hợp các nhóm của các series có thể kết hợp.
type: docs
url: /vi/com.aspose.slides/ichartseriesgroupcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Đại diện cho tập hợp các nhóm của các series có thể kết hợp.

--------------------

1) Mỗi nhóm của series chứa các series với các kiểu có thể kết hợp. Các nhóm của các kiểu series có thể kết hợp được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup. Ngoài ra, mỗi nhóm của series chứa các series được vẽ trên trục chính hoặc trên trục phụ (không cả hai trường hợp trong cùng một nhóm). Vì vậy, nguyên tắc nhóm series là việc nhóm theo các nhóm kiểu đã đề cập ở trên và theo kiểu vẽ trên trục chính/phụ. 2) Nhóm của series chứa một số thuộc tính của series chung cho mỗi series trong nhóm ("Series group properties"). "Series group properties" trong lớp ChartSeriesGroup là đọc/ghi. Mỗi "Series group properties" có thể có một phép chiếu chỉ đọc trong lớp ChartSeries.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Lấy nhóm series theo series. |
| [get_Item(int index)](#get-Item-int-) | Lấy nhóm series theo chỉ mục. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Lấy nhóm series theo series.

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

Lấy nhóm series theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)