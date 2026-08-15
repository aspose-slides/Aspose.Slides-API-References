---
title: get_RewindAudio()
second_title: Aspose.Slides 的 C++ API 參考
description: 判斷音訊在播放後是否會自動倒帶至開始。讀取 bool.
type: docs
weight: 235
url: /zh-hant/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() 方法


判斷音訊在播放後是否會自動倒帶至開始。讀取 **bool**。

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## 備註


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

## 另請參閱

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)