---
title: get_FadeOutDuration()
second_title: Aspose.Slides for C++ API 參考
description: 指定媒體結束淡出所需的時間長度（以毫秒為單位）。讀取 float.
type: docs
weight: 352
url: /zh-hant/aspose.slides/iaudioframe/get_fadeoutduration/
---
## IAudioFrame::get_FadeOutDuration() 方法


指定媒體結束淡出所需的時間長度（以毫秒為單位）。讀取 **float**。

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeOutDuration()=0
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the ending fade for 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 參見

* 類別 [IAudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)