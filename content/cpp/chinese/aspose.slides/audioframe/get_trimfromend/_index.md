---
title: get_TrimFromEnd()
second_title: Aspose.Slides for C++ API 参考
description: 指定在播放期间从媒体末端删除的时间持续长度，单位为毫秒。读取 float。
type: docs
weight: 430
url: /zh/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() 方法

指定在播放期间从媒体末端删除的时间持续长度，单位为毫秒。读取 **float**。

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 将结束修剪时间设置为 2 秒
audioFrame->set_TrimFromEnd(2000.0f);
```

## 另请参阅

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)