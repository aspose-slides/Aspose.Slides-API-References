---
title: get_TrimFromEnd()
second_title: Aspose.Slides C++ API 參考
description: 指定在播放期間從媒體結尾移除的時間長度（以毫秒為單位）。讀取 float.
type: docs
weight: 430
url: /zh-hant/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() 方法


指定在播放期間從媒體結尾移除的時間長度（以毫秒為單位）。讀取 **float**。

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
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

* 類別 [IAudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)