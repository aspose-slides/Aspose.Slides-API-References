---
title: IChartCategoryCollection class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection lớp

Biểu diễn bộ sưu tập của [`IChartCategory`](/slides/python-net/vi/aspose.slides.charts/ichartcategory)

Kiểu IChartCategoryCollection cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`use_cells`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection/use_cells/) | Nếu đúng thì worksheet được sử dụng để lưu trữ các danh mục (trường hợp này hỗ trợ các danh mục đa cấp).<br/>Nếu sai thì worksheet KHÔNG được sử dụng để lưu trữ giá trị (và trường hợp này không hỗ trợ <br/>các danh mục đa cấp).<br/>Đọc/ghi **bool**. |
| [`grouping_level_count`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Trả về số lượng mức nhóm danh mục đã sử dụng.<br/>Lớn hơn một cho các danh mục đa cấp.<br/>Chỉ đọc **int**. |

Lấy phần tử tại chỉ số được chỉ định.

## Chỉ mục

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Phương thức

| Method | Description |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Nếu danh mục tồn tại trong bộ sưu tập, trả về nó. Nếu không, tạo danh mục biểu đồ mới từ [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) và thêm nó vào bộ sưu tập. |
| [`add(self, value)`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection/add/#any) | Tạo [`IChartCategory`](/slides/python-net/vi/aspose.slides.charts/ichartcategory) mới từ giá trị và thêm nó vào bộ sưu tập. |
| [`index_of(self, value)`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Tìm kiếm [`IChartCategory`](/slides/python-net/vi/aspose.slides.charts/ichartcategory) được chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection |
| [`remove(self, value)`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Xóa giá trị được chỉ định. |
| [`remove_at(self, index)`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Xóa phần tử tại chỉ số đã cho. |
| [`clear(self)`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection/clear/#) | Xóa tất cả các phần tử khỏi bộ sưu tập. |


### Xem thêm
* lớp [`IChartCategory`](/slides/python-net/vi/aspose.slides.charts/ichartcategory)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)