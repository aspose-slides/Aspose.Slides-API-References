---
title: get_VolumeValue()
second_title: Aspose.Slides C++ API 参考
description: 返回音频音量的百分比。只读 float.
type: docs
weight: 378
url: /zh/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() 方法


返回音频音量的百分比。只读 **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## 备注


示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 设置起始淡入的持续时间为 200 毫秒
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)