---
title: Hyperlink class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/hyperlink/
---
## Lớp Hyperlink

Biểu diễn một hyperlink.

**Kế thừa:**[`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/vi/aspose.slides/pviobject)

Kiểu Hyperlink cung cấp các thành viên sau:

## Các hàm tạo

| Hàm tạo | Mô tả |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/vi/aspose.slides/hyperlink/__init__/#str) | Tạo một thể hiện của hyperlink. |
| [`__init__(self, slide)`](/slides/python-net/vi/aspose.slides/hyperlink/__init__/#islide) | Tạo một thể hiện của hyperlink trỏ đến slide cụ thể.<br/>            Lưu ý: hyperlink đã tạo phải được gán cho một đối tượng trong cùng một bản trình chiếu, nếu không liên kết sẽ được lưu dưới dạng NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/vi/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Tạo một thể hiện của hyperlink bằng cách sử dụng hyperlink khác làm nguồn, ghi đè các thuộc tính phụ. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`no_action`](/slides/python-net/vi/aspose.slides/hyperlink/no_action/) | Trả về một hyperlink đặc biệt "do nothing".<br/>            Chỉ đọc [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/vi/aspose.slides/hyperlink/media/) | Trả về một hyperlink đặc biệt "play mediafile". Được sử dụng trong AudioFrame và VideoFrame.<br/>            Chỉ đọc [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/vi/aspose.slides/hyperlink/next_slide/) | Trả về một hyperlink tới slide tiếp theo.<br/>            Chỉ đọc [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/vi/aspose.slides/hyperlink/previous_slide/) | Trả về một hyperlink tới slide trước đó.<br/>            Chỉ đọc [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/vi/aspose.slides/hyperlink/first_slide/) | Trả về một hyperlink tới slide đầu tiên của bản trình chiếu.<br/>            Chỉ đọc [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/vi/aspose.slides/hyperlink/last_slide/) | Trả về một hyperlink tới slide cuối cùng của bản trình chiếu.<br/>            Chỉ đọc [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/vi/aspose.slides/hyperlink/last_vieved_slide/) | Trả về một hyperlink tới slide đã xem cuối cùng.<br/>            Chỉ đọc [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/vi/aspose.slides/hyperlink/end_show/) | Trả về một hyperlink kết thúc buổi chiếu.<br/>            Chỉ đọc [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/vi/aspose.slides/hyperlink/action_type/) | Trả về loại hành động của Hyperlink.<br/>            Chỉ đọc [`HyperlinkActionType`](/slides/python-net/vi/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/vi/aspose.slides/hyperlink/external_url/) | Xác định URL bên ngoài.<br/>            Chỉ đọc **str**. |
| [`target_slide`](/slides/python-net/vi/aspose.slides/hyperlink/target_slide/) | Nếu Hyperlink nhắm tới slide cụ thể, trả về slide này.<br/>            Chỉ đọc [`ISlide`](/slides/python-net/vi/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/vi/aspose.slides/hyperlink/external_url_original/) | Đại diện cho một hyperlink được đặt cho phần này mà không quan tâm đến nội dung thực tế của phần.<br/>            <br/>            PowerPoint có hành vi đặc biệt đối với các liên kết và văn bản tương ứng trong một phần. Nó cho phép tạo văn bản cho hyperlink dưới dạng một URL hợp lệ, khác với địa chỉ thực của liên kết. Trong trường hợp này, khi bạn xem liên kết trong cửa sổ chỉnh sửa, nó sẽ được thay đổi để khớp với phần văn bản. Thuộc tính này đại diện cho giá trị gốc của hyperlink. |
| [`target_frame`](/slides/python-net/vi/aspose.slides/hyperlink/target_frame/) | Trả về khung trong bộ khung HTML cha cho mục tiêu<br/>            của hyperlink cha khi tồn tại.<br/>            Đọc/ghi **str**. |
| [`tooltip`](/slides/python-net/vi/aspose.slides/hyperlink/tooltip/) | Trả về chuỗi có thể hiển thị trong giao diện người dùng<br/>            liên quan đến hyperlink cha.<br/>            Đọc/ghi **str**. |
| [`history`](/slides/python-net/vi/aspose.slides/hyperlink/history/) | Xác định liệu mục tiêu của hyperlink cha có được thêm<br/>            vào danh sách hyperlink đã xem khi được kích hoạt hay không.<br/>            Đọc/ghi **bool**. |
| [`highlight_click`](/slides/python-net/vi/aspose.slides/hyperlink/highlight_click/) | Xác định liệu hyperlink có nên được làm nổi bật khi nhấp chuột hay không.<br/>            Đọc/ghi **bool**. |
| [`stop_sound_on_click`](/slides/python-net/vi/aspose.slides/hyperlink/stop_sound_on_click/) | Xác định liệu âm thanh có nên dừng lại khi nhấp vào hyperlink hay không.<br/>            Đọc/ghi **bool**. |
| [`sound`](/slides/python-net/vi/aspose.slides/hyperlink/sound/) | Đại diện cho âm thanh đang phát của hyperlink.<br/>            Đọc/ghi [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/vi/aspose.slides/hyperlink/color_source/) | Đại diện cho nguồn màu của hyperlink - hoặc style hoặc định dạng phần.<br/>            Đọc/ghi [`HyperlinkColorSource`](/slides/python-net/vi/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/vi/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/hyperlink/presentation/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/vi/aspose.slides/hyperlink/equals/#ihyperlink) | Xác định liệu hai thể hiện Hyperlink có bằng nhau hay không. |

### Xem thêm
* lớp [`Hyperlink`](/slides/python-net/vi/aspose.slides/hyperlink)
* lớp [`PVIObject`](/slides/python-net/vi/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)