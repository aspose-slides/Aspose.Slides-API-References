---
title: set_FadeInDuration()
second_title: Aspose.Slides for C++ API 參考手冊
description: 指定媒體首次淡入的時間長度（以毫秒為單位）。寫入 float.
type: docs
weight: 339
url: /zh-hant/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) 方法


指定媒體首次淡入的時間長度（以毫秒為單位）。寫入 **float**。

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定起始淡入的持續時間為 200 毫秒
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## 另見

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)