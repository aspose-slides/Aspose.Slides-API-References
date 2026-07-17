---
title: set_RewindAudio()
second_title: Aspose.Slides C++ API 参考
description: 确定音频在播放结束后是否会自动倒回到起始位置。写入 bool。
type: docs
weight: 248
url: /zh/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) 方法

确定音频在播放结束后是否自动倒回到起始位置。写入 **bool**。

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
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

## 另见

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)