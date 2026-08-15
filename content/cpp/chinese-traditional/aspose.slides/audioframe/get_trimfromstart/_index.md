---
title: get_TrimFromStart()
second_title: Aspose.Slides for C++ API 參考
description: 指定在播放期間從媒體開頭移除的時間長度（以毫秒為單位）。讀取 float.
type: docs
weight: 404
url: /zh-hant/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() 方法

指定在播放時從媒體開頭移除的時間長度（以毫秒為單位）。讀取 **float**。

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the start trimming time 1.5 seconds
audioFrame->set_TrimFromStart(1500.0f);
```

## 另請參閱

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)