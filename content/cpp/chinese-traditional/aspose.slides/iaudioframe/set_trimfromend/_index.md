---
title: set_TrimFromEnd()
second_title: Aspose.Slides C++ API 參考
description: 指定在播放期間從媒體結尾移除的時間長度（毫秒）。寫入 float.
type: docs
weight: 443
url: /zh-hant/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) method


指定在播放期間從媒體結尾移除的時間長度（毫秒）。寫入 **float**。

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定結尾裁剪時間 2 秒
audioFrame->set_TrimFromEnd(2000.0f);
```

## 另見

* 類別 [IAudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)