---
title: IChartData class
second_title: Aspose.Slides cho Python qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides.charts/ichartdata/
---
## IChartData lớp

Đại diện dữ liệu được sử dụng cho việc vẽ biểu đồ.

Kiểu IChartData cung cấp các thành viên sau:

## Thuộc tính

| Property | Mô tả |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/vi/aspose.slides.charts/ichartdata/chart_data_workbook/) | Lấy nhà máy ô để tạo các ô được sử dụng cho chuỗi hoặc danh mục biểu đồ.<br/>Chỉ đọc [`IChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/vi/aspose.slides.charts/ichartdata/series/) | Lấy các chuỗi.<br/>Chỉ đọc [`IChartSeriesCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/vi/aspose.slides.charts/ichartdata/series_groups/) | Lấy các nhóm chuỗi.<br/>Chỉ đọc [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/categories/) | Lấy các danh mục chính (hoặc cả danh mục chính và phụ <br/>nếu thuộc tính [`IChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/use_secondary_categories) là false).<br/>Chỉ đọc [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/use_secondary_categories/) | Nếu false thì thuộc tính [`IChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/secondary_categories) trả về None và dữ liệu <br/>trong thuộc tính [`IChartData.categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/categories) được sử dụng cho cả chuỗi chính và phụ.<br/>Nếu true thì dữ liệu trong thuộc tính [`IChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/secondary_categories) được sử dụng cho chuỗi phụ và dữ liệu <br/>trong thuộc tính [`IChartData.categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/categories) được sử dụng cho chuỗi chính.<br/>Đọc/ghi **bool**. |
| [`secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/secondary_categories/) | Lấy các danh mục phụ nếu thuộc tính [`IChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/use_secondary_categories) là true.<br/>Chỉ đọc [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/vi/aspose.slides.charts/ichartdata/data_source_type/) | Đại diện nguồn dữ liệu của biểu đồ |
| [`external_workbook_path`](/slides/python-net/vi/aspose.slides.charts/ichartdata/external_workbook_path/) | Đại diện đường dẫn đến workbook bên ngoài nếu nguồn dữ liệu là bên ngoài, ngược lại là None |
| [`embedded_workbook_type`](/slides/python-net/vi/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Lấy loại workbook nhúng.<br/>Trả về [`WorkbookType.NOT_DEFINED`](/slides/python-net/vi/aspose.slides.charts/workbooktype/NOT_DEFINED) nếu [`IChartData.data_source_type`](/slides/python-net/vi/aspose.slides.charts/ichartdata/data_source_type) là <br/>[`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/vi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>Chỉ đọc [`WorkbookType`](/slides/python-net/vi/aspose.slides.charts/workbooktype). |

## Phương thức

| Method | Mô tả |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/vi/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ. Dữ liệu biểu đồ sẽ được cập nhật từ workbook mục tiêu. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/vi/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ. |
| [`read_workbook_stream(self)`](/slides/python-net/vi/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Ghi workbook Excel nội bộ vào một luồng trong bộ nhớ. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/vi/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Khởi tạo workbook Excel nội bộ với giá trị do người dùng chỉ định. |
| [`set_range(self, formula)`](/slides/python-net/vi/aspose.slides.charts/ichartdata/set_range/#str) | Đặt phạm vi dữ liệu biểu đồ. Các chuỗi và danh mục sẽ được cập nhật dựa trên phạm vi dữ liệu mới.<br/>Nếu số lượng chuỗi trong phạm vi dữ liệu lớn hơn số chuỗi trong dữ liệu biểu đồ thì các chuỗi bổ sung có cùng kiểu<br/>với chuỗi cuối cùng trong bộ sưu tập hiện tại sẽ được thêm vào cuối bộ sưu tập. |
| [`get_range(self)`](/slides/python-net/vi/aspose.slides.charts/ichartdata/get_range/#) | Lấy phạm vi dữ liệu biểu đồ. |
| [`switch_row_column(self)`](/slides/python-net/vi/aspose.slides.charts/ichartdata/switch_row_column/#) | Hoán đổi dữ liệu qua trục.<br/>Dữ liệu được vẽ trên trục X sẽ chuyển sang trục Y và ngược lại. |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)