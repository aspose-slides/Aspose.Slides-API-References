---
title: set_TrimFromEnd()
second_title: Aspose.Slides for C++ API 參考
description: 指定在播放期間從媒體末端移除的時間長度，單位為毫秒。寫入 float.
type: docs
weight: 443
url: /zh-hant/aspose.slides/audioframe/set_trimfromend/
---
## AudioFrame::set_TrimFromEnd(float) 方法


指定在播放期間從媒體末端移除的時間長度，單位為毫秒。寫入 **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromEnd(float value) override
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定結束裁切時間 2 秒
audioFrame->set_TrimFromEnd(2000.0f);
```

## 另請參閱

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)