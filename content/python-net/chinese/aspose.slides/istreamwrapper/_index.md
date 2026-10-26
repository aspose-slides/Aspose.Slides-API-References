---
title: IStreamWrapper class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/istreamwrapper/
---
## IStreamWrapper 类

Aspose.IO.Stream 的 COM 接口包装器。

IStreamWrapper 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/zh/aspose.slides/istreamwrapper/stream/) | 获取流。<br/>只读 **io.RawIOBase**. |
| [`can_read`](/slides/python-net/zh/aspose.slides/istreamwrapper/can_read/) | 获取一个值，指示当前流是否支持读取。<br/>只读 **bool**. |
| [`can_seek`](/slides/python-net/zh/aspose.slides/istreamwrapper/can_seek/) | 获取一个值，指示当前流是否支持定位。<br/>只读 **bool**. |
| [`can_write`](/slides/python-net/zh/aspose.slides/istreamwrapper/can_write/) | 获取一个值，指示当前流是否支持写入。<br/>只读 **bool**. |
| [`length`](/slides/python-net/zh/aspose.slides/istreamwrapper/length/) | 获取流的字节长度。<br/>只读 **int**. |
| [`position`](/slides/python-net/zh/aspose.slides/istreamwrapper/position/) | 获取当前流中的位置。<br/>只读 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/zh/aspose.slides/istreamwrapper/close/#) | 关闭当前流并释放任何资源。 |
| [`flush(self)`](/slides/python-net/zh/aspose.slides/istreamwrapper/flush/#) | 清除此流的所有缓冲区，并将任何缓冲的数据写入底层设备。 |
| [`read(self, buffer, offset, count)`](/slides/python-net/zh/aspose.slides/istreamwrapper/read/#bytes-int-int) | 从当前流读取一系列字节，并根据读取的字节数前移流中的位置。 |
| [`read_byte(self)`](/slides/python-net/zh/aspose.slides/istreamwrapper/read_byte/#) | 从流中读取一个字节，并将流的位置前移一个字节；如果已到达流的末尾，则返回 -1。 |
| [`seek(self, offset, origin)`](/slides/python-net/zh/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | 设置当前流中的位置 |
| [`write(self, buffer, offset, count)`](/slides/python-net/zh/aspose.slides/istreamwrapper/write/#bytes-int-int) | 向当前流写入一系列字节，并根据写入的字节数前移此流中的当前位置。 |
| [`write_byte(self, value)`](/slides/python-net/zh/aspose.slides/istreamwrapper/write_byte/#int) | 向流的当前位置写入一个字节，并将流的位置前移一个字节。 |


### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)