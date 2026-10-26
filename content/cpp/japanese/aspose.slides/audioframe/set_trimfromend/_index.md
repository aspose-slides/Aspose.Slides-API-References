---
title: set_TrimFromEnd()
second_title: Aspose.Slides for C++ API リファレンス
description: 再生中にメディアの末尾から削除される時間の長さをミリ秒で指定します。書き込みは float です。
type: docs
weight: 443
url: /ja/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) メソッド

再生時にメディアの末尾から削除される時間の長さをミリ秒で指定します。書き込みは **float** です。

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
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

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)