---
title: get_TrimFromEnd()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 再生中にメディアの末尾から削除される時間の長さをミリ秒単位で指定します。Read float.
type: docs
weight: 430
url: /ja/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() メソッド

再生中にメディアの末尾から削除される時間の長さをミリ秒単位で指定します。Read **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
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