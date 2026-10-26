---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个带有嵌入 WAV 文件的新音频帧，并将其添加到形状集合的末尾。嵌入的音频会被添加到 Presentation.Audios 集合中。
type: docs
weight: 248
url: /zh/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 方法

创建一个带有嵌入 WAV 文件的新音频帧，并将其添加到形状集合的末尾。嵌入的音频会添加到 Presentation.Audios 集合中。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新音频帧的 x 坐标，单位为点。 |
| y | **float** | 新音频帧的 y 坐标，单位为点。 |
| width | **float** | 新音频帧的宽度，单位为点。 |
| height | **float** | 新音频帧的高度，单位为点。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含要嵌入的 WAV 音频数据的输入流。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) 方法

创建一个新的音频帧，并使用来自 Presentation.Audios 列表的现有音频对象将其添加到形状集合的末尾。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 新音频帧的 x 坐标，单位为点。 |
| y | **float** | 新音频帧的 y 坐标，单位为点。 |
| width | **float** | 新音频帧的宽度，单位为点。 |
| height | **float** | 新音频帧的高度，单位为点。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 来自 Presentation.Audios 集合的 [IAudio](../../iaudio/) 实例。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAudioFrame](../../iaudioframe/)
* 类 [Stream](../../../system.io/stream/)
* 类 [IShapeCollection](../)
* 类 [IAudio](../../iaudio/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)