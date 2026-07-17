---
title: get_TrimFromStart()
second_title: Aspose.Slides C++ API 参考
description: 指定在播放期间从媒体开头删除的时间持续时间，单位为毫秒。读取 float。
type: docs
weight: 404
url: /zh/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() 方法


指定在播放期间从媒体开头删除的时间持续时间，单位为毫秒。读取 **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## 备注


示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 设置起始剪裁时间 1.5 秒
audioFrame->set_TrimFromStart(1500.0f);
```

## 另请参阅

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)