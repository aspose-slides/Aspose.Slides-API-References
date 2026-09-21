---
title: ChartCategoryCollection class
second_title: Aspose.Slides cho Python qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection lớp

Biểu diễn tập hợp của [`ChartCategory`](/slides/python-net/vi/aspose.slides.charts/chartcategory)

Loại ChartCategoryCollection cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`use_cells`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection/use_cells/) | Nếu true thì worksheet được dùng để lưu trữ các danh mục (trường hợp này hỗ trợ danh mục đa cấp).<br/>Nếu false thì worksheet KHÔNG được dùng để lưu trữ các giá trị (và trường hợp này không hỗ trợ<br/>danh mục đa cấp).<br/>Đọc/ghi **bool**. |
| [`grouping_level_count`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Trả về số lượng mức nhóm danh mục đã sử dụng.<br/>Lớn hơn một cho danh mục đa cấp.<br/>Chỉ đọc **int**. |

Lấy phần tử tại chỉ mục đã chỉ định.

## Chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Nếu danh mục tồn tại trong tập hợp, trả về nó. Nếu không, tạo danh mục biểu đồ mới từ <br/>[`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) và thêm vào tập hợp. |
| [`add(self, value)`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection/add/#any) | Tạo [`ChartCategory`](/slides/python-net/vi/aspose.slides.charts/chartcategory) mới từ giá trị và thêm vào tập hợp. |
| [`index_of(self, value)`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Tìm kiếm [`ChartCategory`](/slides/python-net/vi/aspose.slides.charts/chartcategory) đã chỉ định và trả về chỉ mục bắt đầu từ 0 của lần xuất hiện đầu tiên trong toàn bộ Collection. |
| [`remove(self, value)`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Xóa giá trị đã chỉ định. |
| [`remove_at(self, index)`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Xóa phần tử tại chỉ mục đã cho. |
| [`clear(self)`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection/clear/#) | Xóa tất cả phần tử khỏi tập hợp. |

### Xem thêm
* lớp [`ChartCategory`](/slides/python-net/vi/aspose.slides.charts/chartcategory)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)