---
title: set_VolumeValue()
second_title: Aspose.Slides C++ API 参考
description: 以百分比设置音频音量。写入 float.
type: docs
weight: 391
url: /zh/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) 方法

Sets the audio volume in percents. Write **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## 备注

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 添加音频帧
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 将起始淡入的持续时间设置为 200 毫秒
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类 [AudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)