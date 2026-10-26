---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
建立一個嵌入 WAV 檔案的新音訊框架，並將其插入至在指定索引處的形狀集合。嵌入的音訊會加入至 Presentation.Audios 集合。

### 返回值

The newly created [`IAudioFrame`](/slides/python-net/zh-hant/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入音訊框架的零基索引。 |
| x | **float** | 新音訊框架的 x 座標（單位：點）。 |
| y | **float** | 新音訊框架的 y 座標（單位：點）。 |
| width | **float** | 新音訊框架的寬度（單位：點）。 |
| height | **float** | 新音訊框架的高度（單位：點）。 |
| audio_stream | **io.RawIOBase** | 包含要嵌入的 WAV 音訊資料的輸入串流。 |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
建立一個新音訊框架，並使用 Presentation.Audios 清單中的現有音訊物件，將其插入至在指定索引處的形狀集合。

### 返回值

The newly created [`IAudioFrame`](/slides/python-net/zh-hant/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入音訊框架的零基索引。 |
| x | **float** | 新音訊框架的 x 座標（單位：點）。 |
| y | **float** | 新音訊框架的 y 座標（單位：點）。 |
| width | **float** | 新音訊框架的寬度（單位：點）。 |
| height | **float** | 新音訊框架的高度（單位：點）。 |
| audio | [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio) | 來自 Presentation.Audios 集合的 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio) 實例，用於嵌入。 |



### 另見
* 類別 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio)
* 類別 [`IAudioFrame`](/slides/python-net/zh-hant/aspose.slides/iaudioframe)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)