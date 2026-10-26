---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API 参考
description: "创建一个带有嵌入 WAV 文件的新音频帧，并将其添加到形状集合的末尾。嵌入的音频会添加到 Presentation::get_Audios 集合中。"
type: docs
weight: 287
url: /zh/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) 方法

创建一个带有嵌入 WAV 文件的新音频帧，并将其添加到形状集合的末尾。嵌入的音频会添加到 [Presentation::get_Audios](../../presentation/get_audios/) 集合中。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新音频帧的 x 坐标（以点为单位）。 |
| y | **float** | 新音频帧的 y 坐标（以点为单位）。 |
| width | **float** | 新音频帧的宽度（以点为单位）。 |
| height | **float** | 新音频帧的高度（以点为单位）。 |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含要嵌入的 WAV 音频数据的输入流。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## 备注

以下示例展示了如何创建 [Audio](../../audio/) 帧。 
```cpp
// 实例化一个表示演示文件的 Presentation 类
auto pres = System::MakeObject<Presentation>();

// 获取第一张幻灯片
auto slide = pres->get_Slides()->idx_get(0);
// 将 wav 音频文件加载到流中
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// 添加音频帧
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// 设置音频的播放模式和音量
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// 将 PowerPoint 文件写入磁盘
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) 方法

创建一个新音频帧，并使用来自 [Presentation::get_Audios](../../presentation/get_audios/) 列表的现有音频对象将其添加到形状集合的末尾。

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新音频帧的 x 坐标（以点为单位）。 |
| y | **float** | 新音频帧的 y 坐标（以点为单位）。 |
| width | **float** | 新音频帧的宽度（以点为单位）。 |
| height | **float** | 新音频帧的高度（以点为单位）。 |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | [IAudio](../../iaudio/) 实例，来自 [Presentation::get_Audios](../../presentation/get_audios/) 集合。 |

### 返回值

新创建的 [IAudioFrame](../../iaudioframe/)。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAudioFrame](../../iaudioframe/)
* 类 [Stream](../../../system.io/stream/)
* 类 [ShapeCollection](../)
* 类 [IAudio](../../iaudio/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)