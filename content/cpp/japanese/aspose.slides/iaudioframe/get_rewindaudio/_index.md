---
title: get_RewindAudio()
second_title: Aspose.Slides の C++ API リファレンス
description: オーディオが再生後に自動的に先頭へ巻き戻されるかどうかを判定します。戻り値は bool です。
type: docs
weight: 235
url: /ja/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() メソッド


オーディオが再生後に自動的に先頭に巻き戻されるかどうかを判定します。戻り値は **bool** です。

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
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

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## 参照

* クラス [IAudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)