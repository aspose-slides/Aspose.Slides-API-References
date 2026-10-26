---
title: get_FadeInDuration()
second_title: Aspose.Slides for C++ API リファレンス
description: メディアの初期フェードインの時間の長さ（ミリ秒）を指定します。読み取り float.
type: docs
weight: 326
url: /ja/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() メソッド


メディアの初期フェードインの時間の長さ（ミリ秒）を指定します。読み取り **float**。

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// オーディオ フレームを追加
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 開始フェードの持続時間を200msに設定
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 関連項目

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)