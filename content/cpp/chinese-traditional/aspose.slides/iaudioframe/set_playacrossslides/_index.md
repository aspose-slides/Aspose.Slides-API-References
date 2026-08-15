---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides for C++ API 參考
description: 判斷音訊是否在投影片之間播放。寫入 bool.
type: docs
weight: 222
url: /zh-hant/aspose.slides/iaudioframe/set_playacrossslides/
---
## IAudioFrame::set_PlayAcrossSlides(bool) 方法


判斷音訊是否在投影片之間播放。寫入 **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_PlayAcrossSlides(bool value)=0
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// 新增音訊框架
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// 設定音訊在投影片之間播放
audioFrame->set_PlayAcrossSlides(true);

// 設定音訊在播放後自動倒回起始位置
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## 另請參閱

* 類別 [IAudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)