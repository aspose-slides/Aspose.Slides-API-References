---
title: IGeometryPath class
second_title: Aspose.Slides cho Python qua Tài liệu Tham khảo API .NET
description: 
type: docs
url: /vi/aspose.slides/igeometrypath/
---
## IGeometryPath lớp

Biểu diễn đường hình học của GeometryShape

Kiểu IGeometryPath cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`path_data`](/slides/python-net/vi/aspose.slides/igeometrypath/path_data/) | Trả về đường hình học của GeometryShape dưới dạng một mảng các đoạn đường. |
| [`fill_mode`](/slides/python-net/vi/aspose.slides/igeometrypath/fill_mode/) | Đặt chế độ tô |
| [`stroke`](/slides/python-net/vi/aspose.slides/igeometrypath/stroke/) | Đặt giao diện nét |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/vi/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | Thêm đường thẳng vào cuối đường |
| [`line_to(self, x, y)`](/slides/python-net/vi/aspose.slides/igeometrypath/line_to/#float-float) | Thêm đường thẳng vào cuối đường |
| [`line_to(self, point, index)`](/slides/python-net/vi/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | Thêm đường thẳng vào vị trí xác định của đường |
| [`line_to(self, x, y, index)`](/slides/python-net/vi/aspose.slides/igeometrypath/line_to/#float-float-int) | Thêm đường thẳng vào vị trí xác định của đường |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/vi/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Thêm đường cong Bezier bậc ba vào cuối đường |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/vi/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Thêm đường cong Bezier bậc ba vào cuối đường |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/vi/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Thêm đường cong Bezier bậc ba vào vị trí xác định của đường |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/vi/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Thêm đường cong Bezier bậc ba vào vị trí xác định của đường |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/vi/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Thêm đường cong Bezier bậc hai vào cuối đường |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/vi/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Thêm đường cong Bezier bậc hai vào cuối đường |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/vi/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Thêm đường cong Bezier bậc hai vào vị trí xác định của đường |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/vi/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Thêm đường cong Bezier bậc hai vào vị trí xác định của đường |
| [`move_to(self, point)`](/slides/python-net/vi/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | Đặt vị trí điểm tiếp theo. |
| [`move_to(self, x, y)`](/slides/python-net/vi/aspose.slides/igeometrypath/move_to/#float-float) | Đặt vị trí điểm tiếp theo. |
| [`remove_at(self, index)`](/slides/python-net/vi/aspose.slides/igeometrypath/remove_at/#int) | Xóa đoạn tại chỉ mục xác định của đường hình học. |
| [`close_figure(self)`](/slides/python-net/vi/aspose.slides/igeometrypath/close_figure/#) | Đóng hình hiện tại của đường này |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/vi/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Thêm cung xác định vào đường. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)