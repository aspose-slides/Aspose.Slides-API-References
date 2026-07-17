---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 参考
description: "创建一个嵌入 WAV 文件的新音频帧，并将其插入到指定索引的形状集合中。嵌入的音频会添加到 Presentation::get_Audios 集合中。"
type: docs
weight: 300
url: /zh/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 方法

创建一个嵌入 WAV 文件的新音频框架并将其插入到指定索引的形状集合中。嵌入的音频会添加到 [Presentation::get_Audios](../../presentation/get_audios/) 集合中。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 用于插入音频框架的零基索引。 |
| x | **float** | 新音频框架的 x 坐标，单位为点。 |
| y | **float** | 新音频框架的 y 坐标，单位为点。 |
| width | **float** | 新音频框架的宽度，单位为点。 |
| height | **float** | 新音频框架的高度，单位为点。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含要嵌入的 WAV 音频数据的输入流。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) 方法

创建一个新音频框架，并使用来自 [Presentation::get_Audios](../../presentation/get_audios/) 列表的现有音频对象将其插入到指定索引的形状集合中。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 用于插入音频框架的零基索引。 |
| x | **float** | 新音频框架的 x 坐标，单位为点。 |
| y | **float** | 新音频框架的 y 坐标，单位为点。 |
| width | **float** | 新音频框架的宽度，单位为点。 |
| height | **float** | 新音频框架的高度，单位为点。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | 要嵌入的来自 [Presentation::get_Audios](../../presentation/get_audios/) 集合的 [IAudio](../../iaudio/) 实例。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAudioFrame](../../iaudioframe/)
* 类 [Stream](../../../system.io/stream/)
* 类 [ShapeCollection](../)
* 类 [IAudio](../../iaudio/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)