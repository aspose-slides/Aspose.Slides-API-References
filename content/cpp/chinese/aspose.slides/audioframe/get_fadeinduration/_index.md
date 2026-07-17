---
title: get_FadeInDuration()
second_title: Aspose.Slides C++ API 参考
description: 指定媒体初始淡入的时间持续时间，单位为毫秒。读取 float。
type: docs
weight: 326
url: /zh/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() 方法


指定媒体初始淡入的时间持续时间，单位为毫秒。读取 **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## 备注


示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 设置起始淡入的持续时间为 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)