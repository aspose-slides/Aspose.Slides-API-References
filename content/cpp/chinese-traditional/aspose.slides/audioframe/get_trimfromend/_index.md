---
title: get_TrimFromEnd()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定在播放期間從媒體結尾移除的時間長度（毫秒）。讀取 float.
type: docs
weight: 430
url: /zh-hant/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() 方法

指定在播放期間從媒體結尾移除的時間長度（毫秒）。讀取 **float**。

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## 備註

範例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定結束修剪時間 2 秒
audioFrame->set_TrimFromEnd(2000.0f);
```

## 參見

* 類別 [AudioFrame](../)
* 名稱空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)