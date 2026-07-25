---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API リファレンス
description: 再生中にメディアの先頭から削除される時間の長さ（ミリ秒）を指定します。floatで記述します。
type: docs
weight: 417
url: /ja/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) メソッド


再生中にメディアの先頭から削除される時間の長さ（ミリ秒）を指定します。**float**で記述します。

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// オーディオフレームを追加
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 開始トリミング時間を1.5秒に設定
audioFrame->set_TrimFromStart(1500.0f);
```

## 参照

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)