---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides for C++ API 參考
description: 判斷音訊是否在投影片之間持續播放。讀取 bool.
type: docs
weight: 209
url: /zh-hant/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() 方法


判斷音訊是否在投影片之間持續播放。讀取 **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// 新增音訊框架
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// 設定音訊在投影片之間持續播放
audioFrame->set_PlayAcrossSlides(true);

// 設定音訊在播放後自動倒帶至開始
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```




## 另見

* 類別 [IAudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)