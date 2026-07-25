---
title: get_PlayAcrossSlides()
second_title: C++ 用 Aspose.Slides API リファレンス
description: オーディオがスライド全体で再生されているかどうかを判定します。bool を読み取ります。
type: docs
weight: 209
url: /ja/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() メソッド


オーディオがスライド全体で再生されるかどうかを判定します。読み取り **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## 備考



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// オーディオフレームを追加
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// スライド全体でオーディオを再生するように設定
audioFrame->set_PlayAcrossSlides(true);

// 再生後にオーディオを自動的に先頭に巻き戻すように設定
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## 参照

* クラス [IAudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)