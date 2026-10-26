---
title: IStreamWrapper class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/istreamwrapper/
---
## IStreamWrapper lớp

Aspose.IO.Stream wrapper for COM interface.

The IStreamWrapper type exposes the following members:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/vi/aspose.slides/istreamwrapper/stream/) | Lấy một luồng.<br/>            Chỉ đọc **io.RawIOBase**. |
| [`can_read`](/slides/python-net/vi/aspose.slides/istreamwrapper/can_read/) | Lấy một giá trị cho biết liệu luồng hiện tại có hỗ trợ đọc hay không.<br/>            Chỉ đọc **bool**. |
| [`can_seek`](/slides/python-net/vi/aspose.slides/istreamwrapper/can_seek/) | Lấy một giá trị cho biết liệu luồng hiện tại có hỗ trợ di chuyển vị trí hay không.<br/>            Chỉ đọc **bool**. |
| [`can_write`](/slides/python-net/vi/aspose.slides/istreamwrapper/can_write/) | Lấy một giá trị cho biết liệu luồng hiện tại có hỗ trợ ghi hay không.<br/>            Chỉ đọc **bool**. |
| [`length`](/slides/python-net/vi/aspose.slides/istreamwrapper/length/) | Lấy độ dài tính bằng byte của luồng.<br/>            Chỉ đọc **int**. |
| [`position`](/slides/python-net/vi/aspose.slides/istreamwrapper/position/) | Lấy vị trí trong luồng hiện tại.<br/>            Chỉ đọc **int**. |

## Phương thức

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/vi/aspose.slides/istreamwrapper/close/#) | Đóng luồng hiện tại và giải phóng mọi tài nguyên. |
| [`flush(self)`](/slides/python-net/vi/aspose.slides/istreamwrapper/flush/#) | Xóa tất cả bộ đệm cho luồng này và buộc dữ liệu trong bộ đệm được ghi vào thiết bị nền. |
| [`read(self, buffer, offset, count)`](/slides/python-net/vi/aspose.slides/istreamwrapper/read/#bytes-int-int) | Đọc một dãy byte từ luồng hiện tại và di chuyển vị trí trong luồng theo số byte đã đọc. |
| [`read_byte(self)`](/slides/python-net/vi/aspose.slides/istreamwrapper/read_byte/#) | Đọc một byte từ luồng và di chuyển vị trí trong luồng một byte, hoặc trả về -1 nếu ở cuối luồng. |
| [`seek(self, offset, origin)`](/slides/python-net/vi/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Đặt vị trí trong luồng hiện tại |
| [`write(self, buffer, offset, count)`](/slides/python-net/vi/aspose.slides/istreamwrapper/write/#bytes-int-int) | ghi một dãy byte vào luồng hiện tại và di chuyển vị trí hiện tại trong luồng này theo số byte đã ghi. |
| [`write_byte(self, value)`](/slides/python-net/vi/aspose.slides/istreamwrapper/write_byte/#int) | Ghi một byte vào vị trí hiện tại trong luồng và di chuyển vị trí trong luồng một byte. |

### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)