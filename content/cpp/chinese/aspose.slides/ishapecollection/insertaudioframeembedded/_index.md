---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides C++ API 参考
description: 创建一个带有嵌入 WAV 文件的新音频帧，并将其插入到指定索引的 shape collection 中。嵌入的音频会添加到 Presentation.Audios 集合中。
type: docs
weight: 261
url: /zh/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 方法

创建一个带有嵌入 WAV 文件的新音频帧，并将其插入到指定索引的 shape collection 中。嵌入的音频会添加到 Presentation.Audios 集合中。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 用于插入音频帧的零基索引。 |
| x | **float** | 新音频帧的 x 坐标（单位：点）。 |
| y | **float** | 新音频帧的 y 坐标（单位：点）。 |
| width | **float** | 新音频帧的宽度（单位：点）。 |
| height | **float** | 新音频帧的高度（单位：点）。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含要嵌入的 WAV 音频数据的输入流。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) 方法

创建一个新音频帧，并使用来自 Presentation.Audios 列表的现有音频对象，将其插入到指定索引的 shape collection 中。

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 用于插入音频帧的零基索引。 |
| x | **float** | 新音频帧的 x 坐标（单位：点）。 |
| y | **float** | 新音频帧的 y 坐标（单位：点）。 |
| width | **float** | 新音频帧的宽度（单位：点）。 |
| height | **float** | 新音频帧的高度（单位：点）。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 要嵌入的来自 Presentation.Audios 集合的 [IAudio](../../iaudio/) 实例。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAudioFrame](../../iaudioframe/)
* 类 [Stream](../../../system.io/stream/)
* 类 [IShapeCollection](../)
* 类 [IAudio](../../iaudio/)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)