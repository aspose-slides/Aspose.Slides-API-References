---
title: register_ink_effect_image method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Đăng ký một hình ảnh vào bộ sưu tập các hình ảnh tùy chỉnh được sử dụng để mô phỏng hiệu ứng hình ảnh cho các bút mực.
            Những hình ảnh này được sử dụng khi hiển thị mực với các giá trị [`InkEffectType`](/slides/python-net/vi/aspose.slides.ink/inkeffecttype) cụ thể,
            chẳng hạn như Galaxy, Rainbow, v.v. Bằng cách cung cấp hình ảnh của riêng bạn, bạn có thể kiểm soát cách mỗi hiệu ứng mực xuất hiện.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/vi/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/vi/aspose.slides/iimage) |  |

### Ghi chú
Phương thức này cho phép thay thế các texture hiệu ứng mực mặc định bằng các texture do người dùng định nghĩa,
            điều này đặc biệt hữu ích khi các tài nguyên mặc định bị hạn chế bởi giấy phép hoặc không khả dụng tại thời gian chạy.
            Mỗi cặp giá trị đã đăng ký phải liên kết một giá trị [`InkEffectType`](/slides/python-net/vi/aspose.slides.ink/inkeffecttype) với một đối tượng [`IImage`](/slides/python-net/vi/aspose.slides/iimage) tương ứng
            (ví dụ, Bitmap, hoặc một giao diện ảnh Aspose).

### Xem thêm
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* lớp [`Ink`](/slides/python-net/vi/aspose.slides.ink/ink)
* liệt kê [`InkEffectType`](/slides/python-net/vi/aspose.slides.ink/inkeffecttype)
* module [`aspose.slides.ink`](/slides/python-net/vi/aspose.slides.ink)
* thư viện [`Aspose.Slides`](/slides/python-net)