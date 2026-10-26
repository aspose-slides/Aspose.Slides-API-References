---
title: StreamWrapper class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/streamwrapper/
---
## StreamWrapper 類別

Aspose.IO.Stream 包裝器，用於 COM 介面。

The StreamWrapper type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/stream/) | 取得串流。<br/>            只讀 **io.RawIOBase**. |
| [`can_read`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/can_read/) | 取得指示目前串流是否支援讀取的值。<br/>            只讀 **bool**. |
| [`can_seek`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/can_seek/) | 取得指示目前串流是否支援定位的值。<br/>            只讀 **bool**. |
| [`can_write`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/can_write/) | 取得指示目前串流是否支援寫入的值。<br/>            只讀 **bool**. |
| [`length`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/length/) | 取得串流的位元組長度。<br/>            只讀 **int**. |
| [`position`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/position/) | 取得或設定目前串流內的位置。<br/>            只讀 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/close/#) | 關閉目前的串流並釋放所有資源。 |
| [`flush(self)`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/flush/#) | 清除此串流的所有緩衝區，並使任何緩衝資料寫入底層裝置。 |
| [`read(self, buffer, offset, count)`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/read/#bytes-int-int) | 從目前的串流讀取一系列位元組，並依讀取的位元組數前移串流中的位置。 |
| [`read_byte(self)`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/read_byte/#) | 從串流讀取一個位元組，並將位置前移一個位元組；若已到達串流結束則回傳 -1。 |
| [`seek(self, offset, origin)`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | 設定目前串流內的位置 |
| [`write(self, buffer, offset, count)`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/write/#bytes-int-int) | 將一系列位元組寫入目前的串流，並依寫入的位元組數前移此串流中的目前位置。 |
| [`write_byte(self, value)`](/slides/python-net/zh-hant/aspose.slides/streamwrapper/write_byte/#int) | 將一個位元組寫入串流的目前位置，並將位置前移一個位元組。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)