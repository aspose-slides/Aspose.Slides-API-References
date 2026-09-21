---
title: ICamera class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/icamera/
---
## ICamera lớp

Mô tả Camera.

Kiểu ICamera cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/vi/aspose.slides/icamera/camera_type/) | Kiểu camera<br/>            Đọc/ghi [`CameraPresetType`](/slides/python-net/vi/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/vi/aspose.slides/icamera/field_of_view_angle/) | FOV của Camera (0-180 deg, field of View)<br/>            Đọc/ghi **float**. |
| [`zoom`](/slides/python-net/vi/aspose.slides/icamera/zoom/) | Thu phóng Camera (positive value in percentage)<br/>            Đọc/ghi **float**. |

## Phương thức

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/vi/aspose.slides/icamera/set_rotation/#float-float-float) | Một phép quay được xác định bằng việc sử dụng vĩ độ<br/>            tọa độ, kinh độ tọa độ, và một vòng quay quanh trục <br/>            như vĩ độ và kinh độ.<br/>            Nếu bất kỳ giá trị tọa độ nào là float.NaN, toàn bộ phép quay là không xác định. |
| [`get_rotation(self)`](/slides/python-net/vi/aspose.slides/icamera/get_rotation/#) | Một phép quay được xác định bằng việc sử dụng vĩ độ<br/>            tọa độ, kinh độ tọa độ, và một vòng quay quanh trục <br/>            như vĩ độ và kinh độ.<br/>            phần tử đầu tiên trong mảng trả về - vĩ độ, thứ hai - kinh độ, thứ ba - vòng quay.<br/>            Trả về None nếu không có phép quay nào được xác định. |


### Xem Thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)