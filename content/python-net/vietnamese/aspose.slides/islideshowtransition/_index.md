---
title: ISlideShowTransition class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/islideshowtransition/
---
## ISlideShowTransition lớp

Biểu diễn chuyển tiếp trình chiếu.

Kiểu ISlideShowTransition công khai các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`sound`](/slides/python-net/vi/aspose.slides/islideshowtransition/sound/) | Trả về hoặc thiết lập dữ liệu âm thanh nhúng.<br/>            Đọc-ghi [`IAudio`](/slides/python-net/vi/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/vi/aspose.slides/islideshowtransition/sound_mode/) | Thiết lập hoặc trả về chế độ âm thanh cho chuyển tiếp slide.<br/>            Đọc-ghi [`TransitionSoundMode`](/slides/python-net/vi/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/vi/aspose.slides/islideshowtransition/sound_loop/) | Thuộc tính này xác định liệu âm thanh có lặp lại cho đến khi sự kiện âm thanh tiếp theo xảy ra trong<br/>            trình chiếu.<br/>            Đọc-ghi **bool**. |
| [`advance_on_click`](/slides/python-net/vi/aspose.slides/islideshowtransition/advance_on_click/) | Xác định liệu một cú nhấp chuột sẽ chuyển sang slide tiếp theo hay không. Nếu thuộc tính này không<br/>            được chỉ định thì giá trị true được giả định.<br/>            Đọc-ghi **bool**. |
| [`advance_after`](/slides/python-net/vi/aspose.slides/islideshowtransition/advance_after/) | Thuộc tính này xác định liệu trình chiếu sẽ chuyển sang slide kế tiếp sau một khoảng thời gian nhất định.<br/>            Đọc/ghi **bool**. |
| [`advance_after_time`](/slides/python-net/vi/aspose.slides/islideshowtransition/advance_after_time/) | Xác định thời gian, tính bằng mili giây, sau đó chuyển tiếp sẽ bắt đầu. Cài đặt này<br/>            có thể được sử dụng cùng với thuộc tính advClick. Nếu thuộc tính này không được chỉ định<br/>            thì giả định không có tự động chuyển tiếp.<br/>            Đọc-ghi **int**. |
| [`speed`](/slides/python-net/vi/aspose.slides/islideshowtransition/speed/) | Xác định tốc độ chuyển tiếp sẽ được sử dụng khi chuyển từ slide hiện tại<br/>            sang slide tiếp theo.<br/>            Đọc-ghi [`TransitionSpeed`](/slides/python-net/vi/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/vi/aspose.slides/islideshowtransition/value/) | Giá trị chuyển tiếp trình chiếu.<br/>            Chỉ-đọc [`ITransitionValueBase`](/slides/python-net/vi/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/vi/aspose.slides/islideshowtransition/type/) | Kiểu chuyển tiếp.<br/>            Đọc-ghi [`TransitionType`](/slides/python-net/vi/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/vi/aspose.slides/islideshowtransition/sound_is_built_in/) | Xác định liệu âm thanh này có phải là âm thanh tích hợp sẵn hay không. Nếu thuộc tính này được đặt thành true thì<br/>            ứng dụng tạo ra sẽ được thông báo để kiểm tra thuộc tính name được chỉ định cho âm thanh này<br/>            trong danh sách âm thanh tích hợp sẵn và sau đó có thể hiển thị tên hoặc giao diện người dùng tùy chỉnh nếu cần.<br/>            Đọc-ghi **bool**. |
| [`sound_name`](/slides/python-net/vi/aspose.slides/islideshowtransition/sound_name/) | Xác định tên đọc được cho âm thanh của chuyển tiếp. Thuộc tính [`ISlideShowTransition.sound`](/slides/python-net/vi/aspose.slides/islideshowtransition/sound) phải được gán để lấy hoặc đặt tên âm thanh.<br/>            Đọc-ghi **str**. |
| [`duration`](/slides/python-net/vi/aspose.slides/islideshowtransition/duration/) | Lấy hoặc đặt thời lượng hiệu ứng chuyển tiếp slide tính bằng mili giây.<br/>            Đọc/ghi **int**. |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)