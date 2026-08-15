---
title: get_FadeOutDuration()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定媒體結束淡出時的時間長度（以毫秒為單位）。讀取 float.
type: docs
weight: 352
url: /zh-hant/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() 方法


指定媒體結束淡出時的時間長度（以毫秒為單位）。讀取 **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
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

## 參見

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)