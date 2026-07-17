---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides for C++ API 参考
description: 确定音频是否跨幻灯片播放。写入 bool。
type: docs
weight: 222
url: /zh/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) 方法

确定音频是否跨幻灯片播放。写入 **bool**。

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## 备注

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// 添加 Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// 设置 Audio 在幻灯片之间播放
audioFrame->set_PlayAcrossSlides(true);

// 设置 Audio 在播放后自动倒带到开始
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## 另见

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)