---
title: IDataLabelCollection class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection lớp

Biểu diễn các nhãn chuỗi.

Kiểu IDataLabelCollection cung cấp các thành viên sau:

## Thuộc tính

| Property | Mô tả |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Trả về định dạng mặc định của tất cả các nhãn dữ liệu trong bộ sưu tập.<br/>            Chỉ-đọc [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Đại diện cho định dạng đường dẫn của nhãn dữ liệu.<br/>             Chỉ-đọc [`IChartLinesFormat`](/slides/python-net/vi/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/is_visible/) | False có nghĩa là nhãn dữ liệu không hiển thị mặc định (và do đó tất cả <br/>            cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat đều sai).<br/>            Chỉ-đọc **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Lấy số lượng nhãn dữ liệu có thể nhìn thấy trong bộ sưu tập.<br/>            Chỉ-đọc **int**. |
| [`count`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/count/) | Lấy tổng số nhãn dữ liệu trong bộ sưu tập.<br/>            Chỉ-đọc **int**. |
| [`parent_series`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/parent_series/) | Trả về chuỗi biểu đồ cha.<br/>            Chỉ-đọc [`IChartSeries`](/slides/python-net/vi/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Lấy hoặc đặt loại hình dạng mặc định cho nhãn dữ liệu.<br/>             Trả về [`ShapeType.NOT_DEFINED`](/slides/python-net/vi/aspose.slides/shapetype/NOT_DEFINED) nếu không có hình dạng nào được định nghĩa. |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Lấy nhãn dữ liệu cho điểm dữ liệu có chỉ số được chỉ định.

## Chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`hide(self)`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/hide/#) | Làm cho nhãn dữ liệu ẩn mặc định bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat thành trạng thái false.<br/>            IsVisible sẽ trở thành false sau hành động này. |
| [`index_of(self, value)`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Trả về chỉ mục của DataLabel được chỉ định trong bộ sưu tập. |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)