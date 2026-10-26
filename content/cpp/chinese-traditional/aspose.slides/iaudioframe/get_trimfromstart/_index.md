---
title: get_TrimFromStart()
second_title: Aspose.Slides for C++ API 參考
description: 指定在播放期間從媒體開頭移除的時間持續時間，單位為毫秒。只讀 float.
type: docs
weight: 404
url: /zh-hant/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() 方法


指定在播放期間從媒體開頭移除的時間持續時間，單位為毫秒。只讀 **float**。

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定開始修剪時間 1.5 秒
audioFrame->set_TrimFromStart(1500.0f);
```

## 參見

* 類別 [IAudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)