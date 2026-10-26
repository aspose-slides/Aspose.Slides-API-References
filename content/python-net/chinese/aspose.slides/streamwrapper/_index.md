---
title: StreamWrapper class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/streamwrapper/
---
## StreamWrapper 类

Aspose.IO.Stream 的 COM 接口包装器。

StreamWrapper 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/zh/aspose.slides/streamwrapper/stream/) | 获取流。<br/>            只读 **io.RawIOBase**. |
| [`can_read`](/slides/python-net/zh/aspose.slides/streamwrapper/can_read/) | 获取一个值，指示当前流是否支持读取。<br/>            只读 **bool**. |
| [`can_seek`](/slides/python-net/zh/aspose.slides/streamwrapper/can_seek/) | 获取一个值，指示当前流是否支持定位。<br/>            只读 **bool**. |
| [`can_write`](/slides/python-net/zh/aspose.slides/streamwrapper/can_write/) | 获取一个值，指示当前流是否支持写入。<br/>            只读 **bool**. |
| [`length`](/slides/python-net/zh/aspose.slides/streamwrapper/length/) | 获取流的字节长度。<br/>            只读 **int**. |
| [`position`](/slides/python-net/zh/aspose.slides/streamwrapper/position/) | 获取或设置当前流中的位置。<br/>            只读 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/zh/aspose.slides/streamwrapper/close/#) | 关闭当前流并释放所有资源。 |
| [`flush(self)`](/slides/python-net/zh/aspose.slides/streamwrapper/flush/#) | 清除该流的所有缓冲区，并将任何缓冲的数据写入底层设备。 |
| [`read(self, buffer, offset, count)`](/slides/python-net/zh/aspose.slides/streamwrapper/read/#bytes-int-int) | 从当前流读取一系列字节，并将流中的位置前移读取的字节数。 |
| [`read_byte(self)`](/slides/python-net/zh/aspose.slides/streamwrapper/read_byte/#) | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流末尾，则返回 -1。 |
| [`seek(self, offset, origin)`](/slides/python-net/zh/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | 设置当前流中的位置 |
| [`write(self, buffer, offset, count)`](/slides/python-net/zh/aspose.slides/streamwrapper/write/#bytes-int-int) | 写入一系列字节到当前流，并将该流中的当前位置前移写入的字节数。 |
| [`write_byte(self, value)`](/slides/python-net/zh/aspose.slides/streamwrapper/write_byte/#int) | 向流的当前位置写入一个字节，并将流中的位置前移一个字节。 |

### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)