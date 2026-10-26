---
title: set_VolumeValue()
second_title: Aspose.Slides for C++ API 參考文件
description: 以百分比設定音訊音量。寫入 float.
type: docs
weight: 391
url: /zh-hant/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) 方法


以百分比設定音訊音量。寫入 **float**。

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## 備註


範例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 新增音訊框架
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)