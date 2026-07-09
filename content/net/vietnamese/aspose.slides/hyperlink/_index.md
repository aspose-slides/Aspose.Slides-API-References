---
title: Hyperlink
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu thị một hyperlink.
type: docs
weight: 5120
url: /vi/aspose.slides/hyperlink/
---
## Lớp Hyperlink

Biểu thị một hyperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Tạo một thể hiện của hyperlink trỏ tới một slide cụ thể. Lưu ý: hyperlink được tạo phải được gán cho một đối tượng trong cùng một bản trình chiếu, nếu không liên kết sẽ được lưu dưới dạng NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Tạo một thể hiện của hyperlink. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Tạo một thể hiện của hyperlink bằng cách sử dụng một hyperlink khác làm nguồn, ghi đè các thuộc tính phụ. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Trả về một hyperlink kết thúc buổi chiếu. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Trả về một hyperlink tới slide đầu tiên của bản trình chiếu. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Trả về một hyperlink tới slide cuối cùng của bản trình chiếu. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Trả về một hyperlink tới slide đã xem lần cuối. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Trả về một hyperlink đặc biệt "play mediafile". Được sử dụng trong AudioFrame và VideoFrame. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Trả về một hyperlink tới slide tiếp theo. Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Trả về một hyperlink đặc biệt "do nothing". Chỉ đọc [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Trả về một hyperlink tới slide trước đó. Chỉ đọc [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Trả về kiểu hành động của Hyperlink. Chỉ đọc [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện cơ sở IPresentationComponent. Chỉ đọc [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Biểu thị nguồn màu của hyperlink - hoặc styles hoặc portion format. Đọc/ghi [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Xác định URL bên ngoài. Chỉ đọc String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Biểu thị một hyperlink được đặt cho phần này mà không quan tâm đến nội dung thực tế của phần. PowerPoint xử lý đặc biệt các liên kết và văn bản tương ứng trong một phần. Nó cho phép tạo văn bản cho hyperlink dưới dạng một URL hợp lệ, khác với địa chỉ thực của liên kết. Trong trường hợp này, khi bạn xem liên kết trong cửa sổ chỉnh sửa, nó sẽ được thay đổi để khớp với phần văn bản. Thuộc tính này biểu thị giá trị gốc của hyperlink. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Xác định liệu hyperlink có nên được làm nổi bật khi nhấp chuột hay không. Đọc/ghi Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Xác định liệu mục tiêu của hyperlink cha có được thêm vào danh sách các hyperlink đã xem khi nó được kích hoạt hay không. Đọc/ghi Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Biểu thị âm thanh đang phát của hyperlink. Đọc/ghi [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Xác định liệu âm thanh có nên dừng khi nhấp vào hyperlink hay không. Đọc/ghi Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Trả về khung trong parent HTML frameset cho mục tiêu của hyperlink cha khi nó tồn tại. Đọc/ghi String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Nếu Hyperlink nhắm tới slide cụ thể, trả về slide đó. Chỉ đọc [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Trả về chuỗi có thể hiển thị trong giao diện người dùng và được liên kết với hyperlink cha. Đọc/ghi String. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Xác định xem hai thể hiện Hyperlink có bằng nhau không. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Xác định xem hai thể hiện Hyperlink có bằng nhau không. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Đóng vai trò như hàm băm cho một kiểu cụ thể, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Kiểm tra tính bằng nhau của hai hyperlink. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Kiểm tra tính không bằng nhau của hai hyperlink. |

### Xem thêm

* lớp [PVIObject](../pviobject)
* giao diện [IHyperlink](../ihyperlink)
* không gian tên [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->