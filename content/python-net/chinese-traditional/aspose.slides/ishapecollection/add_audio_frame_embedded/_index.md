---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
建立一個嵌入 WAV 檔案的新音訊框架，並將其添加至形狀集合的末端。嵌入的音訊會加入到 Presentation.Audios 集合中。

### 傳回值

新建立的 [`IAudioFrame`](/slides/python-net/zh-hant/aspose.slides/iaudioframe)。



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新音訊框架的 x 座標，以點為單位。 |
| y | **float** | 新音訊框架的 y 座標，以點為單位。 |
| width | **float** | 新音訊框架的寬度，以點為單位。 |
| height | **float** | 新音訊框架的高度，以點為單位。 |
| audio_stream | **io.RawIOBase** | 包含要嵌入之 WAV 音訊資料的輸入串流。 |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
建立一個新音訊框架，並使用 Presentation.Audios 清單中的現有音訊物件，將其添加至形狀集合的末端。

### 傳回值

新建立的 [`IAudioFrame`](/slides/python-net/zh-hant/aspose.slides/iaudioframe)。



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新音訊框架的 x 座標，以點為單位。 |
| y | **float** | 新音訊框架的 y 座標，以點為單位。 |
| width | **float** | 新音訊框架的寬度，以點為單位。 |
| height | **float** | 新音訊框架的高度，以點為單位。 |
| audio | [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio) | 來自 Presentation.Audios 集合的 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio) 實例。 |



### 另請參閱
* 類別 [`IAudio`](/slides/python-net/zh-hant/aspose.slides/iaudio)
* 類別 [`IAudioFrame`](/slides/python-net/zh-hant/aspose.slides/iaudioframe)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)