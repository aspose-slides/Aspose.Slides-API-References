---
title: set_VolumeValue()
second_title: Aspose.Slides の C++ API リファレンス
description: オーディオの音量をパーセンテージで設定します。floatを書き込みます。
type: docs
weight: 391
url: /ja/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) メソッド


オーディオの音量をパーセンテージで設定します。**float** を書き込みます。

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## 備考


例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// オーディオ フレームを追加
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [AudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)