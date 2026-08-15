---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ API 參考
description: 以百分比回傳音訊音量。讀取 float.
type: docs
weight: 378
url: /zh-hant/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() 方法


回傳以百分比表示的音訊音量。讀取 **float**。

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```

## 備註


範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定起始淡入的持續時間為 200 毫秒
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## 參見

* 類別 [IAudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)