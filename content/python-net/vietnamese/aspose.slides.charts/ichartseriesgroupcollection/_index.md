---
title: IChartSeriesGroupCollection class
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection lớp

Biểu diễn tập hợp các nhóm của series có thể kết hợp.

Kiểu IChartSeriesGroupCollection cung cấp các thành viên sau:

Lấy nhóm series theo chỉ mục.

## Trình chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### Ghi chú

1) Mỗi nhóm series chứa các series có các loại có thể kết hợp. Các nhóm loại series có thể kết hợp được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup. Ngoài ra, mỗi nhóm series chứa các series được vẽ trên trục chính hoặc trên trục phụ (không đồng thời trong cùng một nhóm). Vì vậy, nguyên tắc nhóm series là nhóm theo các nhóm loại đã nêu ở trên và theo loại vẽ chính/phụ.

2) Nhóm series chứa một số thuộc tính series chung cho mỗi series trong nhóm (“thuộc tính nhóm series”). “Thuộc tính nhóm series” trong lớp ChartSeriesGroup là đọc/ghi. Mỗi “thuộc tính nhóm series” có thể có một phép chiếu chỉ-đọc trong lớp ChartSeries.

### Xem thêm
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)