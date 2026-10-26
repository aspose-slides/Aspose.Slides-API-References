---
title: set_TrimFromEnd()
second_title: Aspose.Slides C++ API 参考
description: 指定在播放期间从媒体末尾删除的时间持续时间，单位为毫秒。写入 float。
type: docs
weight: 443
url: /zh/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) 方法

指定在播放期间从媒体末尾删除的时间持续时间，单位为毫秒。写入 **float**。

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 设置结束修剪时间 2 秒
audioFrame->set_TrimFromEnd(2000.0f);
```

## 另请参阅

* 类 [IAudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)