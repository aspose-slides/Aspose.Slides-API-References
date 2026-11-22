---
title: ChartData class
second_title: Aspose.Slides cho Python qua .NET API Tham khảo
description: 
type: docs
url: /vi/aspose.slides.charts/chartdata/
---
## ChartData lớp

Đại diện dữ liệu được sử dụng cho việc vẽ biểu đồ.

Kiểu ChartData cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/vi/aspose.slides.charts/chartdata/chart_data_workbook/) | Lấy factory ô để tạo ô dùng cho chuỗi hoặc danh mục biểu đồ.<br/>            Chỉ đọc [`IChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/vi/aspose.slides.charts/chartdata/series/) | Lấy các chuỗi.<br/>            Chỉ đọc [`IChartSeriesCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/vi/aspose.slides.charts/chartdata/series_groups/) | Lấy các nhóm của chuỗi.<br/>            Chỉ đọc [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/categories/) | Lấy các danh mục chính (hoặc cả danh mục chính và phụ <br/>            nếu thuộc tính [`ChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/use_secondary_categories) là false).<br/>            Chỉ đọc [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/use_secondary_categories/) | Nếu false thì thuộc tính [`ChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/secondary_categories) trả về None và dữ liệu <br/>            trong thuộc tính [`ChartData.categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/categories) được dùng cho cả chuỗi chính và phụ.<br/>            Nếu true thì dữ liệu trong thuộc tính [`ChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/secondary_categories) được dùng cho chuỗi phụ và dữ liệu <br/>            trong thuộc tính [`ChartData.categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/categories) được dùng cho chuỗi chính.<br/>            Đọc/ghi **bool**. |
| [`secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/secondary_categories/) | Lấy các danh mục phụ nếu thuộc tính [`ChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/use_secondary_categories) là true.<br/>            Chỉ đọc [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/vi/aspose.slides.charts/chartdata/data_source_type/) | Đại diện đường dẫn sổ làm việc bên ngoài nếu là nguồn dữ liệu ngoại, nếu không thì None |
| [`external_workbook_path`](/slides/python-net/vi/aspose.slides.charts/chartdata/external_workbook_path/) | Đại diện nguồn dữ liệu của biểu đồ |
| [`embedded_workbook_type`](/slides/python-net/vi/aspose.slides.charts/chartdata/embedded_workbook_type/) | Lấy kiểu của sổ làm việc nhúng.<br/>            Trả về [`WorkbookType.NOT_DEFINED`](/slides/python-net/vi/aspose.slides.charts/workbooktype/NOT_DEFINED) nếu [`ChartData.data_source_type`](/slides/python-net/vi/aspose.slides.charts/chartdata/data_source_type) là <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/vi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Chỉ đọc [`WorkbookType`](/slides/python-net/vi/aspose.slides.charts/workbooktype). |

## Phương thức

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/vi/aspose.slides.charts/chartdata/set_external_workbook/#str) | Đặt sổ làm việc bên ngoài làm nguồn dữ liệu cho biểu đồ. Dữ liệu biểu đồ sẽ được cập nhật từ sổ làm việc đích. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/vi/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Đặt sổ làm việc bên ngoài làm nguồn dữ liệu cho biểu đồ. |
| [`read_workbook_stream(self)`](/slides/python-net/vi/aspose.slides.charts/chartdata/read_workbook_stream/#) | Ghi sổ làm việc Excel nội bộ vào một luồng. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/vi/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Khởi tạo sổ làm việc Excel nội bộ bằng giá trị do người dùng chỉ định. |
| [`get_range(self)`](/slides/python-net/vi/aspose.slides.charts/chartdata/get_range/#) | Lấy phạm vi dữ liệu biểu đồ. |
| [`set_range(self, formula)`](/slides/python-net/vi/aspose.slides.charts/chartdata/set_range/#str) | Đặt phạm vi dữ liệu biểu đồ. Các chuỗi và danh mục sẽ được cập nhật dựa trên phạm vi dữ liệu mới.<br/>            Nếu số lượng chuỗi trong phạm vi dữ liệu lớn hơn số chuỗi trong dữ liệu biểu đồ thì các chuỗi bổ sung có cùng kiểu<br/>            như chuỗi cuối cùng trong bộ sưu tập hiện tại sẽ được thêm vào cuối bộ sưu tập. |
| [`refresh_data(self)`](/slides/python-net/vi/aspose.slides.charts/chartdata/refresh_data/#) | Làm mới dữ liệu biểu đồ bằng cách tải lại từ sổ làm việc nguồn. |
| [`switch_row_column(self)`](/slides/python-net/vi/aspose.slides.charts/chartdata/switch_row_column/#) | Hoán đổi dữ liệu qua trục.<br/>            Dữ liệu được vẽ trên trục X sẽ chuyển sang trục Y và ngược lại. |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)