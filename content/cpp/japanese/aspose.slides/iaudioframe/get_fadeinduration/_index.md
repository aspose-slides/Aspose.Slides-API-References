---
title: get_FadeInDuration()
second_title: Aspose.Slides for C++ API リファレンス
description: メディアの初期フェードインの時間長さをミリ秒単位で指定します。取得は float 型です。
type: docs
weight: 326
url: /ja/aspose.slides/iaudioframe/get_fadeinduration/
---
## IAudioFrame::get_FadeInDuration() メソッド


メディアの最初のフェードインの時間長さをミリ秒単位で指定します。取得 **float**。

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeInDuration()=0
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// オーディオフレームを追加
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 開始フェードの持続時間を200msに設定
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [IAudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)