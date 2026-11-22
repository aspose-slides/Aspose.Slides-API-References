---
title: IDataLabel class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabel/
---
## IDataLabel lớp

Biểu diễn các nhãn của chuỗi.

Kiểu IDataLabel cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_visible`](/slides/python-net/vi/aspose.slides.charts/idatalabel/is_visible/) | False có nghĩa là nhãn dữ liệu không hiển thị (và do đó tất cả các cờ Show*-flags (ShowValue, ...) đều sai).<br/>            Chỉ đọc **bool**. |
| [`data_label_format`](/slides/python-net/vi/aspose.slides.charts/idatalabel/data_label_format/) | Trả về định dạng của nhãn dữ liệu.<br/>            Chỉ đọc [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/vi/aspose.slides.charts/idatalabel/value_from_cell/) | Lấy hoặc đặt ô dữ liệu của workbook. Được áp dụng nếu thuộc tính IDataLabelFormat.ShowLabelValueFromCell bằng true. |
| [`label_shape_type`](/slides/python-net/vi/aspose.slides.charts/idatalabel/label_shape_type/) | Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu.<br/>            Trả về [`ShapeType.NOT_DEFINED`](/slides/python-net/vi/aspose.slides/shapetype/NOT_DEFINED) nếu không có hình dạng nào được xác định. |
| [`x`](/slides/python-net/vi/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/vi/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/vi/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/vi/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/vi/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/vi/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/vi/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/vi/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/vi/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/vi/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/vi/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/vi/aspose.slides.charts/idatalabel/actual_height/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`hide(self)`](/slides/python-net/vi/aspose.slides.charts/idatalabel/hide/#) | Ẩn nhãn dữ liệu bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) thành trạng thái false.<br/>            IsVisible sẽ là false sau thao tác này. |
| [`get_actual_label_text(self)`](/slides/python-net/vi/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Trả về văn bản nhãn thực tế dựa trên cài đặt DataLabelFormat hoặc giá trị TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/vi/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)