---
title: get_FadeOutDuration()
second_title: Aspose.Slides for C++ API リファレンス
description: メディアの終了フェードアウトの時間長をミリ秒単位で指定します。読み取り float。
type: docs
weight: 352
url: /ja/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() メソッド


メディアの終了フェードアウトの時間長をミリ秒単位で指定します。読み取り **float**。

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// オーディオ フレームを追加
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 終了フェードの時間を500msに設定
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)