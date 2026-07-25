---
title: set_FadeInDuration()
second_title: Aspose.Slides for C++ API リファレンス
description: メディアの初期フェードインの時間長をミリ秒で指定します。float を記述します。
type: docs
weight: 339
url: /ja/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) メソッド


メディアの初期フェードインの時間長をミリ秒で指定します。 **float** を記述します。

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// オーディオフレームを追加
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 開始フェードの継続時間を200ミリ秒に設定
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)