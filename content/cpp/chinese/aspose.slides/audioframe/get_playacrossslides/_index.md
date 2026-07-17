---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides C++ API 参考
description: 确定音频是否在幻灯片之间播放。读取 bool.
type: docs
weight: 209
url: /zh/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() 方法


确定音频是否在幻灯片之间播放。读取 **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## 备注



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## 另请参阅

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)