---
title: set_FadeOutDuration()
second_title: Aspose.Slides C++ API 参考
description: 指定媒体结束淡出所持续的时间，单位为毫秒。写入 float。
type: docs
weight: 365
url: /zh/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) 方法

指定媒体结束淡出所持续的时间，单位为毫秒。写入 **float**。

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## 备注

示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 将结束淡出的持续时间设置为 500 毫秒
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)