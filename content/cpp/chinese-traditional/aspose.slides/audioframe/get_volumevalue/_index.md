---
title: get_VolumeValue()
second_title: Aspose.Slides C++ API 參考
description: 返回音量的百分比。讀取 float.
type: docs
weight: 378
url: /zh-hant/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() 方法

返回音量的百分比。讀取 **float**。

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 設定起始淡入的持續時間為 200 毫秒
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)