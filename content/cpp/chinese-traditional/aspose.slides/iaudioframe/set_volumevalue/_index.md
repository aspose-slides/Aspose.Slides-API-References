---
title: set_VolumeValue()
second_title: Aspose.Slides C++ API 參考文件
description: 設定音量百分比。寫入 float.
type: docs
weight: 391
url: /zh-hant/aspose.slides/iaudioframe/set_volumevalue/
---
## IAudioFrame::set_VolumeValue(float) method

設定音量百分比。寫入 **float**。

```cpp
virtual void Aspose::Slides::IAudioFrame::set_VolumeValue(float value)=0
```

## 備註

範例：
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

* 類別 [IAudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)