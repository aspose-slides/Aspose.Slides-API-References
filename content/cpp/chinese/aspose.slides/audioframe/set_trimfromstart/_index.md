---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API 参考
description: 指定在播放期间从媒体开头移除的时间持续量，单位为毫秒。写入 float。
type: docs
weight: 417
url: /zh/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) 方法

指定在播放期间从媒体开头移除的时间持续量，单位为毫秒。写入 **float**。

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 设置开始修剪时间 1.5 秒
audioFrame->set_TrimFromStart(1500.0f);
```

## 另见

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)