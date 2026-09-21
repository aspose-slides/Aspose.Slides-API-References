---
title: StreamWrapper class
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides/streamwrapper/
---
## StreamWrapper lớp

Bọc Aspose.IO.Stream cho giao diện COM.

Kiểu StreamWrapper cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`stream`](/slides/python-net/vi/aspose.slides/streamwrapper/stream/) | Lấy một luồng.<br/>            Chỉ-đọc **io.RawIOBase**. |
| [`can_read`](/slides/python-net/vi/aspose.slides/streamwrapper/can_read/) | Lấy một giá trị cho biết liệu luồng hiện tại có hỗ trợ đọc hay không.<br/>            Chỉ-đọc **bool**. |
| [`can_seek`](/slides/python-net/vi/aspose.slides/streamwrapper/can_seek/) | Lấy một giá trị cho biết liệu luồng hiện tại có hỗ trợ di chuyển vị trí hay không.<br/>            Chỉ-đọc **bool**. |
| [`can_write`](/slides/python-net/vi/aspose.slides/streamwrapper/can_write/) | Lấy một giá trị cho biết liệu luồng hiện tại có hỗ trợ ghi hay không.<br/>            Chỉ-đọc **bool**. |
| [`length`](/slides/python-net/vi/aspose.slides/streamwrapper/length/) | Lấy độ dài tính bằng byte của luồng.<br/>            Chỉ-đọc **int**. |
| [`position`](/slides/python-net/vi/aspose.slides/streamwrapper/position/) | Lấy hoặc đặt vị trí trong luồng hiện tại.<br/>            Chỉ-đọc **int**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`close(self)`](/slides/python-net/vi/aspose.slides/streamwrapper/close/#) | Đóng luồng hiện tại và giải phóng bất kỳ tài nguyên nào. |
| [`flush(self)`](/slides/python-net/vi/aspose.slides/streamwrapper/flush/#) | Xoá tất cả bộ đệm cho luồng này và buộc bất kỳ dữ liệu nào đã được đệm được ghi vào thiết bị nền. |
| [`read(self, buffer, offset, count)`](/slides/python-net/vi/aspose.slides/streamwrapper/read/#bytes-int-int) | Đọc một chuỗi byte từ luồng hiện tại và di chuyển vị trí trong luồng theo số byte đã đọc. |
| [`read_byte(self)`](/slides/python-net/vi/aspose.slides/streamwrapper/read_byte/#) | Đọc một byte từ luồng và di chuyển vị trí trong luồng một byte, hoặc trả về -1 nếu ở cuối luồng. |
| [`seek(self, offset, origin)`](/slides/python-net/vi/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Đặt vị trí trong luồng hiện tại |
| [`write(self, buffer, offset, count)`](/slides/python-net/vi/aspose.slides/streamwrapper/write/#bytes-int-int) | Ghi một chuỗi byte vào luồng hiện tại và di chuyển vị trí hiện tại trong luồng này theo số byte đã ghi. |
| [`write_byte(self, value)`](/slides/python-net/vi/aspose.slides/streamwrapper/write_byte/#int) | Ghi một byte vào vị trí hiện tại trong luồng và di chuyển vị trí trong luồng một byte. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)