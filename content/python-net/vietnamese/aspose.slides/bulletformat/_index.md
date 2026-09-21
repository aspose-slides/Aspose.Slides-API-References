---
title: BulletFormat class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/bulletformat/
---
## BulletFormat lớp

Đại diện cho các thuộc tính định dạng dấu đầu dòng của đoạn văn.

**Kế thừa:**[`BulletFormat`](/slides/python-net/vi/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/vi/aspose.slides/pviobject)

Kiểu BulletFormat hiển thị các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`type`](/slides/python-net/vi/aspose.slides/bulletformat/type/) | Trả về hoặc đặt loại dấu đầu dòng của một đoạn văn không kế thừa.<br/>            Đọc/ghi [`BulletType`](/slides/python-net/vi/aspose.slides/bullettype). |
| [`char`](/slides/python-net/vi/aspose.slides/bulletformat/char/) | Trả về hoặc đặt ký tự dấu đầu dòng của một đoạn văn không kế thừa.<br/>            Đọc/ghi **System.Char**. |
| [`font`](/slides/python-net/vi/aspose.slides/bulletformat/font/) | Trả về hoặc đặt phông chữ dấu đầu dòng của một đoạn văn không kế thừa.<br/>            Đọc/ghi [`IFontData`](/slides/python-net/vi/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/vi/aspose.slides/bulletformat/height/) | Trả về hoặc đặt chiều cao dấu đầu dòng của một đoạn văn không kế thừa.<br/>            Giá trị float.NaN xác định rằng dấu đầu dòng kế thừa chiều cao từ phần đầu tiên trong đoạn văn.<br/>            Đọc/ghi **float**. |
| [`color`](/slides/python-net/vi/aspose.slides/bulletformat/color/) | Trả về định dạng màu của dấu đầu dòng trong một đoạn văn không kế thừa.<br/>            Chỉ đọc [`IColorFormat`](/slides/python-net/vi/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/vi/aspose.slides/bulletformat/numbered_bullet_start_with/) | Trả về hoặc đặt số đầu tiên được sử dụng cho nhóm các dấu đầu dòng được đánh số không kế thừa.<br/>            Đọc/ghi **int**. |
| [`numbered_bullet_style`](/slides/python-net/vi/aspose.slides/bulletformat/numbered_bullet_style/) | Trả về hoặc đặt kiểu của dấu đầu dòng được đánh số không kế thừa.<br/>            Đọc/ghi [`NumberedBulletStyle`](/slides/python-net/vi/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/vi/aspose.slides/bulletformat/is_bullet_hard_color/) | Xác định liệu dấu đầu dòng có màu riêng hay kế thừa nó từ phần đầu tiên trong đoạn văn.<br/>            **NullableBool.True** nếu dấu đầu dòng có màu riêng và **NullableBool.False** nếu dấu đầu dòng<br/>            kế thừa màu từ phần đầu tiên trong đoạn văn.<br/>            Đọc/ghi [`NullableBool`](/slides/python-net/vi/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/vi/aspose.slides/bulletformat/is_bullet_hard_font/) | Xác định liệu dấu đầu dòng có phông chữ riêng hay kế thừa nó từ phần đầu tiên trong đoạn văn.<br/>            **NullableBool.True** nếu dấu đầu dòng có phông chữ riêng và **NullableBool.False** nếu dấu đầu dòng<br/>            kế thừa phông chữ từ phần đầu tiên trong đoạn văn.<br/>            Đọc/ghi [`NullableBool`](/slides/python-net/vi/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/vi/aspose.slides/bulletformat/picture/) | Trả về hình ảnh được sử dụng làm dấu đầu dòng trong một đoạn văn không kế thừa.<br/>            Chỉ đọc [`ISlidesPicture`](/slides/python-net/vi/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/vi/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/bulletformat/presentation/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/vi/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Đặt các dịch chuyển mặc định khác không cho Indent và MarginLeft thực tế của đoạn văn khi bật dấu đầu dòng (giống như PowerPoint làm khi bật dấu đầu dòng/đánh số đoạn văn). Nếu tắt dấu đầu dòng thì chỉ đặt lại Indent và MarginLeft của đoạn văn (giống như PowerPoint làm khi tắt dấu đầu dòng/đánh số đoạn văn). Các dịch chuyển thụt lề được áp dụng dựa trên ngữ cảnh dấu đầu dòng hiện tại - IBulletFormat.Type, .NumberedBulletStyle và FontHeight của phần đầu tiên. Các dịch chuyển thụt lề khác không được áp dụng cho Indent và MarginLeft thực tế của đoạn văn hiện tại (để giá trị kết quả là giá trị cục bộ). |
| [`get_effective(self)`](/slides/python-net/vi/aspose.slides/bulletformat/get_effective/#) | Lấy dữ liệu định dạng dấu đầu dòng thực tế với việc kế thừa đã được áp dụng. |

### Xem thêm
* lớp [`BulletFormat`](/slides/python-net/vi/aspose.slides/bulletformat)
* lớp [`PVIObject`](/slides/python-net/vi/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)