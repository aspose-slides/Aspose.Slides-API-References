---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API リファレンス
description: 再生中にメディアの先頭から削除される時間の長さをミリ秒で指定します。floatを書き込みます。
type: docs
weight: 417
url: /ja/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) メソッド


再生中にメディアの先頭から削除される時間の長さをミリ秒で指定します。**float**を書き込みます。

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
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

* クラス [IAudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)