---
title: IBulletFormat class
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/ibulletformat/
---
## IBulletFormat lớp

Represents paragraph bullet formatting properties.

The IBulletFormat type exposes the following members:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/vi/aspose.slides/ibulletformat/type/) | Trả về hoặc đặt loại dấu đầu dòng của một đoạn văn không kế thừa.<br/>            Đọc/ghi [`BulletType`](/slides/python-net/vi/aspose.slides/bullettype). |
| [`char`](/slides/python-net/vi/aspose.slides/ibulletformat/char/) | Trả về hoặc đặt ký tự dấu đầu dòng của một đoạn văn không kế thừa.<br/>            Đọc/ghi **System.Char**. |
| [`font`](/slides/python-net/vi/aspose.slides/ibulletformat/font/) | Trả về hoặc đặt phông chữ dấu đầu dòng của một đoạn văn không kế thừa.<br/>            Đọc/ghi [`IFontData`](/slides/python-net/vi/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/vi/aspose.slides/ibulletformat/height/) | Trả về hoặc đặt chiều cao dấu đầu dòng của một đoạn văn không kế thừa.<br/>            Giá trị float.NaN xác định rằng dấu đầu dòng kế thừa chiều cao từ phần đầu tiên trong đoạn văn.<br/>            Đọc/ghi **float**. |
| [`color`](/slides/python-net/vi/aspose.slides/ibulletformat/color/) | Trả về định dạng màu của dấu đầu dòng trong một đoạn văn không kế thừa.<br/>            Chỉ đọc [`IColorFormat`](/slides/python-net/vi/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/vi/aspose.slides/ibulletformat/picture/) | Trả về hình ảnh được sử dụng làm dấu đầu dòng trong một đoạn văn không kế thừa.<br/>            Chỉ đọc [`ISlidesPicture`](/slides/python-net/vi/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/vi/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Trả về hoặc đặt số đầu tiên được sử dụng cho nhóm dấu đầu dòng có số thứ tự trong một đoạn văn không kế thừa.<br/>            Đọc/ghi **int**. |
| [`numbered_bullet_style`](/slides/python-net/vi/aspose.slides/ibulletformat/numbered_bullet_style/) | Trả về hoặc đặt kiểu của dấu đầu dòng có số thứ tự trong một đoạn văn không kế thừa.<br/>            Đọc/ghi [`IBulletFormat.numbered_bullet_style`](/slides/python-net/vi/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/vi/aspose.slides/ibulletformat/is_bullet_hard_color/) | Xác định xem dấu đầu dòng có màu riêng hay kế thừa từ phần đầu tiên trong đoạn văn.<br/>            **NullableBool.True**  nếu dấu đầu dòng có màu riêng và **NullableBool.False**  nếu dấu đầu dòng<br/>            kế thừa màu từ phần đầu tiên trong đoạn văn.<br/>            Đọc/ghi [`NullableBool`](/slides/python-net/vi/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/vi/aspose.slides/ibulletformat/is_bullet_hard_font/) | Xác định xem dấu đầu dòng có phông chữ riêng hay kế thừa từ phần đầu tiên trong đoạn văn.<br/>            **NullableBool.True**  nếu dấu đầu dòng có phông chữ riêng và **NullableBool.False**  nếu dấu đầu dòng<br/>            kế thừa phông chữ từ phần đầu tiên trong đoạn văn.<br/>            Đọc/ghi [`NullableBool`](/slides/python-net/vi/aspose.slides/nullablebool). |

## Phương thức

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/vi/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Thiết lập các dịch chuyển khác không mặc định cho Indent và MarginLeft thực tế của đoạn văn khi bật dấu đầu dòng (giống như PowerPoint làm khi bật dấu đầu dòng/đánh số đoạn văn). Nếu dấu đầu dòng bị tắt thì chỉ đặt lại Indent và MarginLeft của đoạn văn (giống như PowerPoint làm khi tắt dấu đầu dòng/đánh số đoạn văn). Các dịch chuyển thụt lề được áp dụng dựa trên ngữ cảnh dấu đầu dòng hiện tại - IBulletFormat.Type, .NumberedBulletStyle và FontHeight của phần đầu tiên. Các dịch chuyển thụt lề khác không được áp dụng cho Indent và MarginLeft thực tế của đoạn văn hiện tại (đưa các giá trị kết quả thành giá trị cục bộ). |
| [`get_effective(self)`](/slides/python-net/vi/aspose.slides/ibulletformat/get_effective/#) | Lấy dữ liệu định dạng dấu đầu dòng hiệu quả với tính kế thừa đã được áp dụng. |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)