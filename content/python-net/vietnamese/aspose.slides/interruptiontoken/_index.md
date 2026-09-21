---
title: InterruptionToken class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/interruptiontoken/
---
## InterruptionToken lớp

Lớp này đại diện cho token được sử dụng để thông báo cho các tác vụ chạy lâu liệu đã có yêu cầu ngắt hay chưa.

Kiểu InterruptionToken cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`none`](/slides/python-net/vi/aspose.slides/interruptiontoken/none/) | Biểu diễn một token ngắt rỗng.<br/>            Các hoạt động chạy lâu sẽ không bao giờ bị ngắt qua [`InterruptionTokenSource.interrupt`](/slides/python-net/vi/aspose.slides/interruptiontokensource/interrupt)<br/>            khi sử dụng token này. |
| [`is_interruption_requested`](/slides/python-net/vi/aspose.slides/interruptiontoken/is_interruption_requested/) | Trả về **bool**.true nếu ngắt đã được yêu cầu. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/vi/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Ném một OperationCanceledException nếu<br/>            ngắt đã được yêu cầu. |

### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)