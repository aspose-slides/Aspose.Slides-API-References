---
title: add_video method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
從另一個簡報中新增影片檔案的副本。

### 返回

已添加的影片。



```python
def add_video(self, video):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo) | 來源影片。 |


## add_video(self, video_data) {#bytes}
從位元組陣列建立並新增影片至簡報。

### 返回

已添加的影片。



```python
def add_video(self, video_data):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| video_data | **bytes** | 影片位元組。 |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
從串流建立並新增影片至簡報。

### 返回

已添加的 [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo)。



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 用於新增影片檔案的串流。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior) | 將套用於串流的行為。 |



### 另見
* 類別 [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo)
* 類別 [`IVideoCollection`](/slides/python-net/zh-hant/aspose.slides/ivideocollection)
* 列舉 [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)