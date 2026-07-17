---
title: get_FadeOutDuration()
second_title: Aspose.Slides C++ API 参考
description: 指定媒体结束淡出时的时间持续时间（毫秒）。读取 float.
type: docs
weight: 352
url: /zh/aspose.slides/iaudioframe/get_fadeoutduration/
---
## IAudioFrame::get_FadeOutDuration() 方法

指定媒体结束淡出时的时间持续时间（毫秒）。读取 **float**。

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeOutDuration()=0
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the ending fade for 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [IAudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)