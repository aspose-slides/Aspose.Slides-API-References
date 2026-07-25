---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides for C++ API リファレンス
description: スライド全体でオーディオが再生されているかどうかを判定します。読み取り型は bool。
type: docs
weight: 209
url: /ja/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() メソッド


スライド全体でオーディオが再生されるかどうかを判定します。読み取り **bool**。

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## 備考



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Audio フレームを追加
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// スライド全体でオーディオを再生するように設定
audioFrame->set_PlayAcrossSlides(true);

// 再生後に自動的にオーディオを先頭に巻き戻すように設定
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## 参照

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)