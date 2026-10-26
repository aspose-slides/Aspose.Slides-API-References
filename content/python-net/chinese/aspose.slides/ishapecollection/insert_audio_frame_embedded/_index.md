---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
创建一个嵌入 WAV 文件的新音频帧并将其插入到指定索引处的形状集合中。嵌入的音频会添加到 Presentation.Audios 集合中。

### 返回

新创建的 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)。



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入音频帧的基于零的索引。 |
| x | **float** | 新音频帧的 x 坐标，单位为点。 |
| y | **float** | 新音频帧的 y 坐标，单位为点。 |
| width | **float** | 新音频帧的宽度，单位为点。 |
| height | **float** | 新音频帧的高度，单位为点。 |
| audio_stream | **io.RawIOBase** | 包含要嵌入的 WAV 音频数据的输入流。 |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
创建一个新音频帧，并使用 Presentation.Audios 列表中的现有音频对象将其插入到指定索引处的形状集合中。

### 返回

新创建的 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)。



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 要插入音频帧的基于零的索引。 |
| x | **float** | 新音频帧的 x 坐标，单位为点。 |
| y | **float** | 新音频帧的 y 坐标，单位为点。 |
| width | **float** | 新音频帧的宽度，单位为点。 |
| height | **float** | 新音频帧的高度，单位为点。 |
| audio | [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio) | 要嵌入的来自 Presentation.Audios 集合的 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio) 实例。 |



### 另见
* 类 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio)
* 类 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)