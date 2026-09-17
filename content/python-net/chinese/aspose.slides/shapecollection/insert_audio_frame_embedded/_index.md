---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
创建一个带有嵌入 WAV 文件的新音频框，并将其插入到指定索引的形状集合中。嵌入的音频会添加到 Presentation.Audios 集合中。

### 返回

新创建的 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)。

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio_stream | **io.RawIOBase** | An input stream containing WAV audio data to embed. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
创建一个新音频框，并使用来自 Presentation.Audios 列表的现有音频对象，将其插入到指定索引的形状集合中。

### 返回

新创建的 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)。

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the audio frame. |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio | [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio) | An [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio) instance from the Presentation.Audios collection to embed. |



### 另请参阅
* 类 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio)
* 类 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)