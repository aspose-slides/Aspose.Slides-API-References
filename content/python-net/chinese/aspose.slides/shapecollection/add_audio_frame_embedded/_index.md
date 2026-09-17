---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
创建一个带嵌入 WAV 文件的新音频框架，并将其添加到形状集合的末尾。嵌入的音频会添加到 Presentation.Audios 集合中。

### 返回
新创建的 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)。

```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新音频框架的 x 坐标，单位为点。 |
| y | **float** | 新音频框架的 y 坐标，单位为点。 |
| width | **float** | 新音频框架的宽度，单位为点。 |
| height | **float** | 新音频框架的高度，单位为点。 |
| audio_stream | **io.RawIOBase** | 包含要嵌入的 WAV 音频数据的输入流。 |

## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
创建一个新音频框架，并使用来自 Presentation.Audios 列表的现有音频对象将其添加到形状集合的末尾。

### 返回
新创建的 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)。

```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新音频框架的 x 坐标，单位为点。 |
| y | **float** | 新音频框架的 y 坐标，单位为点。 |
| width | **float** | 新音频框架的宽度，单位为点。 |
| height | **float** | 新音频框架的高度，单位为点。 |
| audio | [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio) | 来自 Presentation.Audios 集合的 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio) 实例。 |

### 另请参阅
* 类 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio)
* 类 [`IAudioFrame`](/slides/python-net/zh/aspose.slides/iaudioframe)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)