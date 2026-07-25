---
title: set_RewindAudio()
second_title: Aspose.Slides の C++ API リファレンス
description: 再生後にオーディオが自動的に開始位置に巻き戻されるかどうかを決定します。書き込みは bool 型です。
type: docs
weight: 248
url: /ja/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) メソッド


再生後にオーディオが自動的に開始位置に巻き戻されるかどうかを決定します。書き込みは **bool** 型です。

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## 備考



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// オーディオフレームを追加
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// スライド全体でオーディオを再生するように設定
audioFrame->set_PlayAcrossSlides(true);

// 再生後にオーディオを自動的に開始位置に巻き戻すように設定
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## 参照

* クラス [IAudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)