---
title: GeometryPath class
second_title: Aspose.Slides cho Python qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides/geometrypath/
---
## GeometryPath lớp

Biểu diễn đường hình học của GeometryShape

Kiểu GeometryPath cung cấp các thành viên sau:

## Hàm khởi tạo

| Constructor | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides/geometrypath/__init__/#) | Tạo một thể hiện của GeometryPath |

## Thuộc tính

| Property | Mô tả |
| :- | :- |
| [`path_data`](/slides/python-net/vi/aspose.slides/geometrypath/path_data/) | Trả về đường hình học của GeometryShape dưới dạng mảng các đoạn đường. |
| [`fill_mode`](/slides/python-net/vi/aspose.slides/geometrypath/fill_mode/) | Đặt chế độ tô |
| [`stroke`](/slides/python-net/vi/aspose.slides/geometrypath/stroke/) | Đặt giao diện nét |

## Phương thức

| Method | Mô tả |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/vi/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Thêm đường thẳng vào cuối đường |
| [`line_to(self, x, y)`](/slides/python-net/vi/aspose.slides/geometrypath/line_to/#float-float) | Thêm đường thẳng vào cuối đường |
| [`line_to(self, point, index)`](/slides/python-net/vi/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Thêm đường thẳng vào vị trí được chỉ định của đường |
| [`line_to(self, x, y, index)`](/slides/python-net/vi/aspose.slides/geometrypath/line_to/#float-float-int) | Thêm đường thẳng vào vị trí được chỉ định của đường |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/vi/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Thêm đường cong Bézier bậc ba vào cuối đường |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/vi/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Thêm đường cong Bézier bậc ba vào cuối đường |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/vi/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Thêm đường cong Bézier bậc ba vào vị trí được chỉ định của đường |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/vi/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Thêm đường cong Bézier bậc ba vào vị trí được chỉ định của đường |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/vi/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Thêm đường cong Bézier bậc hai vào cuối đường |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/vi/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Thêm đường cong Bézier bậc hai vào cuối đường |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/vi/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Thêm đường cong Bézier bậc hai vào vị trí được chỉ định của đường |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/vi/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Thêm đường cong Bézier bậc hai vào vị trí được chỉ định của đường |
| [`move_to(self, point)`](/slides/python-net/vi/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Đặt vị trí điểm tiếp theo. |
| [`move_to(self, x, y)`](/slides/python-net/vi/aspose.slides/geometrypath/move_to/#float-float) | Đặt vị trí điểm tiếp theo. |
| [`remove_at(self, index)`](/slides/python-net/vi/aspose.slides/geometrypath/remove_at/#int) | Xóa đoạn tại chỉ mục được chỉ định của đường hình học. |
| [`close_figure(self)`](/slides/python-net/vi/aspose.slides/geometrypath/close_figure/#) | Đóng hình hiện tại của đường này |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/vi/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Thêm cung được chỉ định vào đường. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)