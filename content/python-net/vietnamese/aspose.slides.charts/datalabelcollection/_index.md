---
title: DataLabelCollection class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection lớp

Đại diện cho các nhãn của chuỗi.

Kiểu DataLabelCollection cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/chart/) | Returns the parent chart.<br/>            Read-only [`IChart`](/slides/python-net/vi/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/is_visible/) | False có nghĩa là nhãn dữ liệu không hiển thị theo mặc định (và do đó tất cả <br/>            Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat là false).<br/>            Read-only **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Lấy số lượng nhãn dữ liệu hiển thị trong bộ sưu tập.<br/>            Read-only **int**. |
| [`count`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/count/) | Lấy tổng số nhãn dữ liệu trong bộ sưu tập.<br/>            Read-only **int**. |
| [`default_data_label_format`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Lấy định dạng nhãn dữ liệu mặc định.<br/>            Read-only [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Đại diện cho định dạng đường dẫn của nhãn dữ liệu.<br/>             Read-only [`IChartLinesFormat`](/slides/python-net/vi/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/parent_series/) | Lấy chuỗi cha.<br/>            Read-only [`IChartSeries`](/slides/python-net/vi/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | Lấy hoặc thiết lập kiểu hình dạng mặc định cho nhãn dữ liệu.<br/>             Returns [`ShapeType.NOT_DEFINED`](/slides/python-net/vi/aspose.slides/shapetype/NOT_DEFINED) nếu không có hình dạng nào được định nghĩa. |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/presentation/) |  |

Lấy nhãn dữ liệu cho điểm dữ liệu với chỉ mục được chỉ định.

## Trình chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`hide(self)`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/hide/#) | Đặt nhãn dữ liệu ẩn theo mặc định bằng cách đặt tất cả các Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat thành trạng thái false.<br/>            IsVisible sẽ là false sau thao tác này. |
| [`index_of(self, value)`](/slides/python-net/vi/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Trả về chỉ mục của DataLabel được chỉ định trong bộ sưu tập. |

### Xem thêm
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)