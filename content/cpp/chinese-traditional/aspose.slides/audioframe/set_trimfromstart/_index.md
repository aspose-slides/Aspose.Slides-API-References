---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API 參考
description: 指定在播放期間從媒體的開始處移除的時間長度（毫秒）。寫入 float。
type: docs
weight: 417
url: /zh-hant/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) 方法


指定在播放期間從媒體的開始處移除的時間長度（毫秒）。寫入 **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## 備註


範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定開始修剪時間 1.5 秒
audioFrame->set_TrimFromStart(1500.0f);
```

## 另見

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)