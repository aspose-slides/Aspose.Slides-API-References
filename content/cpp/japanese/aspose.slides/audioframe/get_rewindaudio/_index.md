---
title: get_RewindAudio()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 再生後にオーディオが自動的に開始位置まで巻き戻されるかどうかを判定します。読み取り bool.
type: docs
weight: 235
url: /ja/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() メソッド


再生後にオーディオが自動的に開始位置まで巻き戻されるかどうかを判断します。読み取り **bool**。

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## 備考



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// オーディオフレームを追加
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// スライド全体で再生するようにオーディオを設定
audioFrame->set_PlayAcrossSlides(true);

// 再生後に自動的に開始位置へ巻き戻すようにオーディオを設定
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## 参照

* クラス [AudioFrame](../)
* ネームスペース [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)