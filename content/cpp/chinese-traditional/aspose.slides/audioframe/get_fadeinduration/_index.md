---
title: get_FadeInDuration()
second_title: Aspose.Slides for C++ API 參考
description: 指定媒體初始淡入的時間長度（毫秒）。讀取 float.
type: docs
weight: 326
url: /zh-hant/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() 方法


指定媒體初始淡入的時間持續長度（毫秒）。讀取 **float**。

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定起始淡入的持續時間為 200 毫秒
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 參見

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)