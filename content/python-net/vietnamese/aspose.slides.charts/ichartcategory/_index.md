---
title: IChartCategory class
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartcategory/
---
## IChartCategory lớp

Đại diện cho các danh mục biểu đồ.

Kiểu IChartCategory tiết lộ các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/use_cell/) | Nếu true thì thuộc tính AsCell là thực tế. Nói cách khác, worksheet được sử dụng để lưu trữ danh mục (trường hợp này hỗ trợ danh mục đa cấp).<br/>            Nếu false thì thuộc tính AsLiteral là thực tế. Nói cách khác, worksheet KHÔNG được sử dụng để lưu trữ danh mục (và trường hợp này không hỗ trợ danh mục đa cấp).<br/>            Chỉ đọc **bool**. |
| [`as_cell`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/as_cell/) | Trả về hoặc thiết lập đối tượng IChartDataCell.<br/>            Nếu danh mục đa cấp thì sử dụng đối tượng IChartDataCell cho cấp độ "0".<br/>            Đọc/ghi [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/as_literal/) | Trả về hoặc thiết lập AsLiteral nếu UseCell là false.<br/>            Đọc/ghi **any**. |
| [`value`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/value/) | Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value.<br/>            Nếu UseCell là false thì thuộc tính này đại diện cho thuộc tính AsLiteral.<br/>            Đọc/ghi **any**. |
| [`cached_value`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/cached_value/) | Lấy giá trị đã lưu trong bộ nhớ cache của một danh mục biểu đồ.<br/>            Chỉ đọc [`ICachedChartValue`](/slides/python-net/vi/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/grouping_levels/) | Bộ chứa được quản lý của các giá trị của các cấp độ nhóm danh mục biểu đồ.<br/>            Danh mục đa cấp chứa nhiều hơn một cấp độ nhóm.<br/>            Chỉ mục các cấp độ nhóm bắt đầu từ zero.<br/>            Chỉ đọc [`IChartCategoryLevelsManager`](/slides/python-net/vi/aspose.slides.charts/ichartcategorylevelsmanager). |

## Phương thức

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/remove/#) | Xóa danh mục khỏi biểu đồ. |


### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)