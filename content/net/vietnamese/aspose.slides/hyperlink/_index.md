---
title: Hyperlink
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Biểu diễn một siêu liên kết.
type: docs
weight: 5140
url: /vi/aspose.slides/hyperlink/
---
## Lớp Hyperlink

Biểu diễn một siêu liên kết.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Tạo một thể hiện của siêu liên kết trỏ tới một slide cụ thể. Lưu ý: siêu liên kết đã tạo nên được gán cho một đối tượng trong cùng bản trình chiếu, nếu không liên kết sẽ được lưu dưới dạng NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Tạo một thể hiện của siêu liên kết. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Tạo một thể hiện của siêu liên kết bằng cách sử dụng một siêu liên kết khác làm nguồn, ghi đè các thuộc tính phụ. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Trả về một siêu liên kết kết thúc buổi trình chiếu. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Trả về một siêu liên kết tới slide đầu tiên của bản trình chiếu. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Trả về một siêu liên kết tới slide cuối cùng của bản trình chiếu. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Trả về một siêu liên kết tới slide đã xem cuối cùng. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Trả về một siêu liên kết đặc biệt "play mediafile". Được dùng trong AudioFrame và VideoFrame. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Trả về một siêu liên kết tới slide tiếp theo. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Trả về một siêu liên kết đặc biệt "do nothing". Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Trả về một siêu liên kết tới slide trước đó. Chỉ đọc [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Trả về kiểu hành động của Hyperlink. Chỉ đọc [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện cơ bản IPresentationComponent. Chỉ đọc [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Đại diện nguồn màu của siêu liên kết - hoặc style hoặc định dạng phần. Đọc/ghi [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Xác định URL bên ngoài. Chỉ đọc String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Đại diện một siêu liên kết được đặt cho phần này mà không xét tới nội dung thực tế của phần. PowerPoint có hành vi đặc biệt đối với các liên kết và văn bản tương ứng trong một phần. Nó cho phép tạo văn bản cho siêu liên kết dưới dạng một URL hợp lệ, khác với địa chỉ thực của liên kết. Trong trường hợp này, khi bạn xem liên kết trong cửa sổ chỉnh sửa, nó sẽ được thay đổi để khớp với phần văn bản. Thuộc tính này đại diện giá trị gốc của siêu liên kết. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Xác định liệu siêu liên kết có nên được làm nổi bật khi nhấp chuột hay không. Đọc/ghi Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. Đọc/ghi Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Đại diện âm thanh phát của siêu liên kết. Đọc/ghi [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Xác định liệu âm thanh có nên dừng lại khi nhấp vào siêu liên kết hay không. Đọc/ghi Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Trả về khung trong khung HTML cha cho mục tiêu của siêu liên kết cha khi có. Đọc/ghi String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Nếu Hyperlink nhắm tới một slide cụ thể, trả về slide đó. Chỉ đọc [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Trả về chuỗi có thể được hiển thị trong giao diện người dùng liên kết với siêu liên kết cha. Đọc/ghi String. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Xác định liệu hai thể hiện Hyperlink có bằng nhau hay không. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Xác định liệu hai thể hiện Hyperlink có bằng nhau hay không. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Đóng vai trò là hàm băm cho một kiểu cụ thể, thích hợp cho việc sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Kiểm tra tính bằng nhau của hai siêu liên kết. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Kiểm tra tính không bằng nhau của hai siêu liên kết. |

### Xem Thêm

* lớp [PVIObject](../pviobject)
* giao diện [IHyperlink](../ihyperlink)
* không gian tên [Aspose.Slides](../../aspose.slides)
* bộ lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->