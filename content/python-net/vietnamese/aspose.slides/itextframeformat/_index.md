---
title: ITextFrameFormat class
second_title: Aspose.Slides cho Python qua .NET Tham khảo API
description: 
type: docs
url: /vi/aspose.slides/itextframeformat/
---
## ITextFrameFormat lớp

Chứa các thuộc tính định dạng của TextFrame.

Kiểu ITextFrameFormat cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`text_style`](/slides/python-net/vi/aspose.slides/itextframeformat/text_style/) | Trả về kiểu của văn bản.<br/>            Chỉ đọc [`ITextStyle`](/slides/python-net/vi/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/vi/aspose.slides/itextframeformat/margin_left/) | Trả về hoặc đặt lề trái (điểm) trong một TextFrame.<br/>            Đọc/ghi **float**. |
| [`margin_right`](/slides/python-net/vi/aspose.slides/itextframeformat/margin_right/) | Trả về hoặc đặt lề phải (điểm) trong một TextFrame.<br/>            Đọc/ghi **float**. |
| [`margin_top`](/slides/python-net/vi/aspose.slides/itextframeformat/margin_top/) | Trả về hoặc đặt lề trên (điểm) trong một TextFrame.<br/>            Đọc/ghi **float**. |
| [`margin_bottom`](/slides/python-net/vi/aspose.slides/itextframeformat/margin_bottom/) | Trả về hoặc đặt lề dưới (điểm) trong một TextFrame.<br/>            Đọc/ghi **float**. |
| [`wrap_text`](/slides/python-net/vi/aspose.slides/itextframeformat/wrap_text/) | **True** nếu văn bản được cuộn tại các lề của TextFrame.<br/>            Đọc/ghi [`NullableBool`](/slides/python-net/vi/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/vi/aspose.slides/itextframeformat/anchoring_type/) | Trả về hoặc đặt văn bản neo dọc trong một TextFrame.<br/>            Đọc/ghi [`TextAnchorType`](/slides/python-net/vi/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/vi/aspose.slides/itextframeformat/center_text/) | Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang.<br/>            Đọc/ghi [`NullableBool`](/slides/python-net/vi/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/vi/aspose.slides/itextframeformat/text_vertical_type/) | Xác định hướng của văn bản.<br/>            Giá trị kết quả của góc quay văn bản trực quan được tổng hợp từ thuộc tính này và góc tùy chỉnh<br/>            trong thuộc tính RotationAngle.<br/>            Đọc/ghi [`TextVerticalType`](/slides/python-net/vi/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/vi/aspose.slides/itextframeformat/autofit_type/) | Trả về hoặc đặt chế độ tự động vừa văn bản.<br/>            Đọc/ghi [`TextAutofitType`](/slides/python-net/vi/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/vi/aspose.slides/itextframeformat/column_count/) | Trả về hoặc đặt số cột trong vùng văn bản.<br/>            Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt thành 0.<br/>            Giá trị 0 có nghĩa là giá trị không xác định.<br/>            Đọc/ghi **int**. |
| [`column_spacing`](/slides/python-net/vi/aspose.slides/itextframeformat/column_spacing/) | Trả về hoặc đặt khoảng cách giữa các cột văn bản trong vùng văn bản (đơn vị điểm). Điều này chỉ áp dụng <br/>            khi có hơn 1 cột.<br/>            Giá trị này phải là số dương. Nếu không, giá trị sẽ được đặt thành 0.<br/>            Đọc/ghi **float**. |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/itextframeformat/three_d_format/) | Trả về đối tượng ThreeDFormat đại diện cho các thuộc tính hiệu ứng 3D cho văn bản.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/vi/aspose.slides/itextframeformat/keep_text_flat/) | Trả về hoặc đặt việc giữ văn bản ra khỏi cảnh 3D hoàn toàn.<br/>            Đọc/ghi **bool**. |
| [`rotation_angle`](/slides/python-net/vi/aspose.slides/itextframeformat/rotation_angle/) | Xác định góc quay tùy chỉnh được áp dụng cho văn bản trong hộp bao quanh. Nếu không<br/>            được chỉ định, góc quay của hình dạng đi kèm sẽ được sử dụng. Nếu được chỉ định, thì điều này sẽ<br/>            được áp dụng độc lập với hình dạng. Nghĩa là hình dạng có thể có góc quay áp dụng thêm<br/>            ngoài việc văn bản tự mình có góc quay.<br/>            Giá trị kết quả của góc quay văn bản trực quan được tổng hợp từ thuộc tính này và loại dọc đã định sẵn<br/>            trong thuộc tính TextVerticalType.<br/>            Đọc/ghi **float**. |
| [`transform`](/slides/python-net/vi/aspose.slides/itextframeformat/transform/) | Trả về hoặc đặt hình dạng cuộn văn bản.<br/>            Đọc/ghi [`TextShapeType`](/slides/python-net/vi/aspose.slides/textshapetype). |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/vi/aspose.slides/itextframeformat/get_effective/#) | Trả về dữ liệu định dạng khung văn bản hiệu quả với tính kế thừa được áp dụng. |

### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)