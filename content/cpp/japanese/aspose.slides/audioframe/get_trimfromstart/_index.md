---
title: get_TrimFromStart()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 再生中にメディアの先頭から削除される時間の長さをミリ秒で指定します。読み取りは floatです。
type: docs
weight: 404
url: /ja/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() メソッド


再生中にメディアの先頭から削除される時間の長さをミリ秒で指定します。読み取り **float**。

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// オーディオ フレームを追加
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 開始トリミング時間を 1.5 秒に設定
audioFrame->set_TrimFromStart(1500.0f);
```

## 参照

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)