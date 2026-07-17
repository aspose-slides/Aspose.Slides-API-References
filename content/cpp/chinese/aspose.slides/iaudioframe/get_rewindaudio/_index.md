---
title: get_RewindAudio()
second_title: Aspose.Slides C++ API 参考
description: 确定音频在播放后是否自动倒回到开始。读取 bool.
type: docs
weight: 235
url: /zh/aspose.slides/iaudioframe/get_rewindaudio/
---
## IAudioFrame::get_RewindAudio() 方法


确定音频在播放后是否自动倒回到开始。读取 **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_RewindAudio()=0
```

## 备注



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// 添加音频帧
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// 设置音频在幻灯片之间播放
audioFrame->set_PlayAcrossSlides(true);

// 设置音频在播放后自动倒回到开始
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## 另见

* 类 [IAudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)