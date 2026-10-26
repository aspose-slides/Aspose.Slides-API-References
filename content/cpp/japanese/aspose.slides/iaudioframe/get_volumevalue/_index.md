---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ API リファレンス
description: 音量をパーセントで返します。float を読み取ります。
type: docs
weight: 378
url: /ja/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() メソッド


音声の音量をパーセントで返します。読み取り **float**。

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
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

* クラス [IAudioFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)