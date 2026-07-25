---
title: set_FadeOutDuration()
second_title: Aspose.Slides for C++ API リファレンス
description: メディアの終了フェードアウトの時間長さをミリ秒で指定します。floatを書き込みます。
type: docs
weight: 365
url: /ja/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) メソッド


メディアのエンドフェードアウトの時間長さをミリ秒で指定します。**float** を書き込み。

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// オーディオフレームを追加
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 終了フェードの時間を500ミリ秒に設定
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)