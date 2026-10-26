---
title: get_FadeOutDuration()
second_title: Aspose.Slides の C++ API リファレンス
description: メディアの終了フェードアウトの時間をミリ秒で指定します。読み取りは float です。
type: docs
weight: 352
url: /ja/aspose.slides/iaudioframe/get_fadeoutduration/
---
## IAudioFrame::get_FadeOutDuration() メソッド


メディアの終了フェードアウトの時間をミリ秒で指定します。読み取り **float**。

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeOutDuration()=0
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

## 関連項目

* クラス [IAudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)