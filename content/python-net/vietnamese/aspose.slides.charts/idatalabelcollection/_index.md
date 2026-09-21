---
title: IDataLabelCollection class
second_title: Aspose.Slides cho Python thông qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection lớp

Biểu thị các nhãn của một chuỗi.

Kiểu IDataLabelCollection cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Trả về định dạng mặc định của tất cả các nhãn dữ liệu trong bộ sưu tập.<br/>            Chỉ đọc [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Biểu thị định dạng các đường dẫn của nhãn dữ liệu.<br/>             Chỉ đọc [`IChartLinesFormat`](/slides/python-net/vi/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/is_visible/) | False có nghĩa là nhãn dữ liệu không hiển thị theo mặc định (và do đó tất cả các cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat đều là false).<br/>            Chỉ đọc **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Lấy số lượng nhãn dữ liệu hiển thị trong bộ sưu tập.<br/>            Chỉ đọc **int**. |
| [`count`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/count/) | Lấy số lượng tất cả các nhãn dữ liệu trong bộ sưu tập.<br/>            Chỉ đọc **int**. |
| [`parent_series`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/parent_series/) | Trả về chuỗi biểu đồ cha.<br/>            Chỉ đọc [`IChartSeries`](/slides/python-net/vi/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Lấy nhãn dữ liệu cho điểm dữ liệu có chỉ mục được chỉ định.

## Trình truy cập chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`hide(self)`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/hide/#) | Đặt nhãn dữ liệu ẩn theo mặc định bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) của thuộc tính DefaultDataLabelFormat thành trạng thái false.<br/>            IsVisible sẽ là false sau thao tác này. |
| [`index_of(self, value)`](/slides/python-net/vi/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Trả về chỉ mục của DataLabel được chỉ định trong bộ sưu tập. |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)