---
title: ChartCategory class
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartcategory/
---
## ChartCategory lớp

Đại diện cho các danh mục biểu đồ.

Kiểu ChartCategory cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/vi/aspose.slides.charts/chartcategory/use_cell/) | Nếu true thì thuộc tính AsCell là thực tế. Nói cách khác, worksheet được sử dụng để <br/>            lưu trữ danh mục (trường hợp này hỗ trợ danh mục đa cấp).<br/>            Nếu false thì thuộc tính AsLiteral là thực tế. Nói cách khác, worksheet KHÔNG được sử dụng <br/>            để lưu trữ danh mục (và trường hợp này không hỗ trợ danh mục đa cấp).<br/>            Chỉ đọc **bool**. |
| [`as_cell`](/slides/python-net/vi/aspose.slides.charts/chartcategory/as_cell/) | Trả về hoặc thiết lập đối tượng IChartDataCell.<br/>            Nếu danh mục là đa cấp thì sử dụng đối tượng IChartDataCell cho cấp "0".<br/>            Đọc/ghi [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/vi/aspose.slides.charts/chartcategory/as_literal/) | Trả về hoặc thiết lập đối tượng AsLiteral.<br/>            Đọc/ghi **any**. |
| [`value`](/slides/python-net/vi/aspose.slides.charts/chartcategory/value/) | Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value.<br/>            Nếu UseCell là false thì thuộc tính này đại diện cho thuộc tính AsLiteral.<br/>            Đọc/ghi **any**. |
| [`grouping_levels`](/slides/python-net/vi/aspose.slides.charts/chartcategory/grouping_levels/) | Bộ chứa được quản lý của các giá trị ở các cấp nhóm danh mục biểu đồ.<br/>            Danh mục đa cấp chứa nhiều hơn một cấp nhóm.<br/>            Chỉ số cấp nhóm bắt đầu từ không.<br/>            Chỉ đọc [`IChartCategoryLevelsManager`](/slides/python-net/vi/aspose.slides.charts/ichartcategorylevelsmanager). |

## Phương thức

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/vi/aspose.slides.charts/chartcategory/remove/#) | Xóa danh mục khỏi biểu đồ. |


### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)