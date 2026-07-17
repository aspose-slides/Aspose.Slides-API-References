---
title: get_TrimFromStart()
second_title: Aspose.Slides C++ API 参考
description: 指定在播放期间要从媒体开头去除的时间持续长度，单位为毫秒。读取 float.
type: docs
weight: 404
url: /zh/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() 方法

指定在播放期间要从媒体开头去除的时间持续长度，单位为毫秒。读取 **float**。

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## 备注


示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 设置起始剪切时间 1.5 秒
audioFrame->set_TrimFromStart(1500.0f);
```

## 另见

* 类 [IAudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)