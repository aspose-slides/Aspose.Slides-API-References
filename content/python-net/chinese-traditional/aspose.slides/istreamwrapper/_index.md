---
title: IStreamWrapper class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/istreamwrapper/
---
## IStreamWrapper 類別

Aspose.IO.Stream wrapper for COM interface.

The IStreamWrapper type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/stream/) | 取得一個串流。<br/>            唯讀 **io.RawIOBase**. |
| [`can_read`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/can_read/) | 取得指示目前串流是否支援讀取的值。<br/>            唯讀 **bool**. |
| [`can_seek`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/can_seek/) | 取得指示目前串流是否支援定位的值。<br/>            唯讀 **bool**. |
| [`can_write`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/can_write/) | 取得指示目前串流是否支援寫入的值。<br/>            唯讀 **bool**. |
| [`length`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/length/) | 取得串流的位元組長度。<br/>            唯讀 **int**. |
| [`position`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/position/) | 取得目前串流中的位置。<br/>            唯讀 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/close/#) | 關閉目前的串流並釋放所有資源。 |
| [`flush(self)`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/flush/#) | 清除此串流的所有緩衝區，並使任何緩衝的資料寫入底層裝置。 |
| [`read(self, buffer, offset, count)`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/read/#bytes-int-int) | 從目前的串流讀取一系列位元組，並依讀取的位元組數前進串流中的位置。 |
| [`read_byte(self)`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/read_byte/#) | 從串流讀取一個位元組，並將位置前進一個位元組；若已到達串流結尾則回傳 -1。 |
| [`seek(self, offset, origin)`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | 設定目前串流中的位置。 |
| [`write(self, buffer, offset, count)`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/write/#bytes-int-int) | 將一系列位元組寫入目前的串流，並依寫入的位元組數前進此串流中的位置。 |
| [`write_byte(self, value)`](/slides/python-net/zh-hant/aspose.slides/istreamwrapper/write_byte/#int) | 在串流的目前位置寫入一個位元組，並將位置前進一個位元組。 |

### 另請參考
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)