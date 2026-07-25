---
title: set_TrimFromEnd()
second_title: Aspose.Slides の C++ API リファレンス
description: 再生中にメディアの末尾から削除される時間の長さ（ミリ秒単位）を指定します。floatを書き込みます。
type: docs
weight: 443
url: /ja/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) メソッド

メディアの再生中に末尾から削除される時間の長さをミリ秒単位で指定します。**float**を書き込みます。

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## 備考

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// オーディオフレームを追加
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 終了トリミング時間を2秒に設定
audioFrame->set_TrimFromEnd(2000.0f);
```

## 参照

* クラス [IAudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)