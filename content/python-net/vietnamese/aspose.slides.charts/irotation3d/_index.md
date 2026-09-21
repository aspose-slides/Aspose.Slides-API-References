---
title: IRotation3D class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/irotation3d/
---
## IRotation3D lớp

Đại diện cho phép quay 3D của biểu đồ.

Kiểu IRotation3D cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`rotation_x`](/slides/python-net/vi/aspose.slides.charts/irotation3d/rotation_x/) | Trả về hoặc đặt góc quay quanh trục X, tức là hướng Y cho biểu đồ 3D (giữa -90 và 90 độ).<br/>            Thuộc tính này phù hợp với mục 21.2.2.157 rotX (X Rotation) trong ECMA-376 và với tùy chọn "Y Rotation" trong PowerPoint 2007+.<br/>            Đọc/ghi **int**. |
| [`rotation_y`](/slides/python-net/vi/aspose.slides.charts/irotation3d/rotation_y/) | Trả về hoặc đặt góc quay quanh trục Y, tức là hướng X cho biểu đồ 3D (giữa 0 và 360 độ).<br/>            Thuộc tính này phù hợp với mục 21.2.158 rotY (Y Rotation) trong ECMA-376 và với tùy chọn "X Rotation" trong PowerPoint 2007+.<br/>            Đọc/ghi **int**. |
| [`perspective`](/slides/python-net/vi/aspose.slides.charts/irotation3d/perspective/) | Trả về hoặc đặt giá trị phối cảnh (góc trường nhìn) cho biểu đồ 3D (giữa 0 và 100).<br/>            Bị bỏ qua nếu giá trị thuộc tính RightAngleAxes là true.<br/>            Đọc/ghi **int**. |
| [`right_angle_axes`](/slides/python-net/vi/aspose.slides.charts/irotation3d/right_angle_axes/) | Xác định liệu các trục của biểu đồ có vuông góc hay không, thay vì được vẽ theo phối cảnh.<br/>            Nói cách khác, nó xác định liệu các góc của trục biểu đồ có độc lập với việc quay hoặc nâng của biểu đồ hay không.<br/>            Đọc/ghi **bool**. |
| [`depth_percents`](/slides/python-net/vi/aspose.slides.charts/irotation3d/depth_percents/) | Trả về hoặc đặt độ sâu của biểu đồ 3D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 20 và 2000 phần trăm).<br/>            Đọc/ghi **int**. |
| [`height_percents`](/slides/python-net/vi/aspose.slides.charts/irotation3d/height_percents/) | Xác định chiều cao của biểu đồ 3-D dưới dạng phần trăm của chiều rộng biểu đồ (giữa 5 và 500 phần trăm).<br/>            Đọc/ghi **int**. |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)