---
title: Rectangle class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: Lưu trữ một tập hợp bốn số nguyên biểu thị vị trí và kích thước của một hình chữ nhật.
type: docs
url: /vi/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Lớp Rectangle

Lưu trữ một tập hợp bốn số nguyên biểu thị vị trí và kích thước của một hình chữ nhật. Tương thích với .NET `System.Drawing.Rectangle`.

Kiểu Rectangle cung cấp các thành viên sau:

## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/vi/aspose.slides/rectangle/__init__/#int-int-int-int) | Tạo một hình chữ nhật với vị trí và kích thước được chỉ định. Các giá trị kiểu float được cắt làm số nguyên. |

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`x`](/slides/python-net/vi/aspose.slides/rectangle/x/) | Lấy tọa độ x của góc trên-trái của hình chữ nhật này.<br/>            Chỉ đọc **int**. |
| [`y`](/slides/python-net/vi/aspose.slides/rectangle/y/) | Lấy tọa độ y của góc trên-trái của hình chữ nhật này.<br/>            Chỉ đọc **int**. |
| [`width`](/slides/python-net/vi/aspose.slides/rectangle/width/) | Lấy độ rộng của hình chữ nhật này.<br/>            Chỉ đọc **int**. |
| [`height`](/slides/python-net/vi/aspose.slides/rectangle/height/) | Lấy độ cao của hình chữ nhật này.<br/>            Chỉ đọc **int**. |
| [`left`](/slides/python-net/vi/aspose.slides/rectangle/left/) | Lấy tọa độ x của cạnh trái của hình chữ nhật này. Bằng với `x`.<br/>            Chỉ đọc **int**. |
| [`top`](/slides/python-net/vi/aspose.slides/rectangle/top/) | Lấy tọa độ y của cạnh trên của hình chữ nhật này. Bằng với `y`.<br/>            Chỉ đọc **int**. |
| [`right`](/slides/python-net/vi/aspose.slides/rectangle/right/) | Lấy tọa độ x bằng tổng của `x` và `width` của hình chữ nhật này.<br/>            Chỉ đọc **int**. |
| [`bottom`](/slides/python-net/vi/aspose.slides/rectangle/bottom/) | Lấy tọa độ y bằng tổng của `y` và `height` của hình chữ nhật này.<br/>            Chỉ đọc **int**. |
| [`is_empty`](/slides/python-net/vi/aspose.slides/rectangle/is_empty/) | Xác định xem tất cả các thuộc tính số của hình chữ nhật này có giá trị bằng không hay không.<br/>            Chỉ đọc **bool**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/vi/aspose.slides/rectangle/contains/#int-int) | Xác định xem điểm được chỉ định có nằm trong hình chữ nhật này hay không. |
| [`contains(self, point)`](/slides/python-net/vi/aspose.slides/rectangle/contains/#point) | Xác định xem điểm được chỉ định có nằm trong hình chữ nhật này hay không. |
| [`contains(self, rect)`](/slides/python-net/vi/aspose.slides/rectangle/contains/#rectangle) | Xác định xem vùng hình chữ nhật được biểu diễn bởi `rect` có hoàn toàn nằm trong hình chữ nhật này hay không. |

### Ghi chú

Các hình chữ nhật được so sánh theo vị trí và kích thước bằng `==` và có thể được sử dụng làm khóa của từ điển hoặc thành viên của tập hợp.

### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)