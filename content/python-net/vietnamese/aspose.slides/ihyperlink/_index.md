---
title: IHyperlink class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ihyperlink/
---
## IHyperlink lớp

Represents a hyperlink.

The IHyperlink type exposes the following members:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`action_type`](/slides/python-net/vi/aspose.slides/ihyperlink/action_type/) | Trả về loại hành động của HyperLinkEx.<br/>            Chỉ-đọc [`HyperlinkActionType`](/slides/python-net/vi/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/vi/aspose.slides/ihyperlink/external_url/) | Xác định URL bên ngoài.<br/>            Nếu thuộc tính này không phải None thì thuộc tính TargetSlide sẽ là None.<br/>            Chỉ-đọc **str**. |
| [`external_url_original`](/slides/python-net/vi/aspose.slides/ihyperlink/external_url_original/) | Biểu diễn một hyperlink được thiết lập cho phần này mà không xét đến nội dung thực tế của phần.<br/>            <br/>            PowerPoint xử lý đặc biệt các liên kết và văn bản tương ứng của chúng trong một phần. Nó cho phép tạo văn bản cho hyperlink dưới dạng một URL hợp lệ, khác với địa chỉ thực của liên kết. Trong trường hợp này, khi bạn xem liên kết trong cửa sổ chỉnh sửa, nó sẽ được thay đổi để phù hợp với phần văn bản. Thuộc tính này biểu diễn giá trị gốc của hyperlink. |
| [`target_slide`](/slides/python-net/vi/aspose.slides/ihyperlink/target_slide/) | Nếu HyperlinkEx nhắm mục tiêu một slide cụ thể, trả về slide đó.<br/>            Nếu thuộc tính này không phải None thì thuộc tính ExternalUrl sẽ là None.<br/>            Chỉ-đọc [`ISlide`](/slides/python-net/vi/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/vi/aspose.slides/ihyperlink/target_frame/) | Trả về frame trong bộ khung HTML cha cho mục tiêu<br/>            của hyperlink cha khi tồn tại.<br/>            Đọc/ghi **str**. |
| [`tooltip`](/slides/python-net/vi/aspose.slides/ihyperlink/tooltip/) | Trả về chuỗi có thể được hiển thị trong giao diện người dùng<br/>            liên quan đến hyperlink cha.<br/>            Đọc/ghi **str**. |
| [`history`](/slides/python-net/vi/aspose.slides/ihyperlink/history/) | Xác định xem mục tiêu của hyperlink cha có nên được thêm<br/>            vào danh sách các hyperlink đã xem khi được gọi không.<br/>            Đọc/ghi **bool**. |
| [`highlight_click`](/slides/python-net/vi/aspose.slides/ihyperlink/highlight_click/) | Xác định xem hyperlink có nên được làm nổi bật khi nhấp chuột không.<br/>            Đọc/ghi **bool**. |
| [`stop_sound_on_click`](/slides/python-net/vi/aspose.slides/ihyperlink/stop_sound_on_click/) | Xác định xem âm thanh có nên bị dừng khi nhấp vào hyperlink không.<br/>            Đọc/ghi **bool**. |
| [`sound`](/slides/python-net/vi/aspose.slides/ihyperlink/sound/) | Biểu diễn âm thanh đang phát của hyperlink.<br/>            Đọc/ghi [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/vi/aspose.slides/ihyperlink/color_source/) | Biểu diễn nguồn màu của hyperlink - có thể là style hoặc định dạng phần.<br/>            Đọc/ghi [`HyperlinkColorSource`](/slides/python-net/vi/aspose.slides/hyperlinkcolorsource). |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/vi/aspose.slides/ihyperlink/equals/#ihyperlink) | Xác định xem hai thể hiện Hyperlink có bằng nhau hay không. |

### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)