---
title: set_FadeOutDuration()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 指定媒體結束淡出的持續時間（以毫秒為單位）。寫入 float.
type: docs
weight: 365
url: /zh-hant/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) 方法

指定媒體結束淡出的持續時間（以毫秒為單位）。寫入 **float**。

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## 備註

範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定結束淡出的持續時間為 500 毫秒
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 另見

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)