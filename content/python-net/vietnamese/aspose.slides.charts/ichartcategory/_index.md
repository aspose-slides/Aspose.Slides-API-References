---
title: IChartCategory class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartcategory/
---
## IChartCategory lớp

Đại diện cho các danh mục biểu đồ.

Kiểu IChartCategory cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`use_cell`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/use_cell/) | Nếu đúng thì thuộc tính AsCell có giá trị. Nói cách khác, worksheet được dùng để <br/>            lưu trữ danh mục (trường hợp này hỗ trợ danh mục đa cấp).<br/>            Nếu sai thì thuộc tính AsLiteral có giá trị. Nói cách khác, worksheet KHÔNG được dùng <br/>            để lưu trữ danh mục (và trường hợp này không hỗ trợ danh mục đa cấp).<br/>            Chỉ đọc **bool**. |
| [`as_cell`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/as_cell/) | Trả về hoặc đặt đối tượng IChartDataCell.<br/>            Nếu danh mục đa cấp thì sử dụng đối tượng IChartDataCell cho mức “0”.<br/>            Đọc/ghi [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/as_literal/) | Trả về hoặc đặt AsLiteral nếu UseCell là false.<br/>            Đọc/ghi **any**. |
| [`value`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/value/) | Nếu UseCell là true thì thuộc tính này đại diện cho thuộc tính AsCell.Value.<br/>            Nếu UseCell là false thì thuộc tính này đại diện cho thuộc tính AsLiteral.<br/>            Đọc/ghi **any**. |
| [`grouping_levels`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/grouping_levels/) | Bộ chứa được quản lý của các giá trị của các mức nhóm danh mục biểu đồ.<br/>            Danh mục đa cấp chứa hơn một mức nhóm.<br/>            Chỉ mục các mức nhóm bắt đầu từ 0.<br/>            Chỉ đọc [`IChartCategoryLevelsManager`](/slides/python-net/vi/aspose.slides.charts/ichartcategorylevelsmanager). |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`remove(self)`](/slides/python-net/vi/aspose.slides.charts/ichartcategory/remove/#) | Xóa danh mục khỏi biểu đồ. |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)