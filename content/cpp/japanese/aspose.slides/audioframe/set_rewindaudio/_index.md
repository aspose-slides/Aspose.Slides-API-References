---
title: set_RewindAudio()
second_title: Aspose.Slides for C++ API リファレンス
description: 再生後に音声が自動的に開始位置へ巻き戻されるかどうかを決定します。bool を書き込みます。
type: docs
weight: 248
url: /ja/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) メソッド


再生後に音声が自動的に開始位置へ巻き戻されるかどうかを決定します。**bool** を書き込みます。

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## 備考



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

## 参照

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)