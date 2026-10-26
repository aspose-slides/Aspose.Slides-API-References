---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API リファレンス
description: トリム開始 [ms]
type: docs
weight: 222
url: /ja/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) メソッド


トリム開始 [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## 備考


例: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//トリミング開始時刻を1秒に設定
videoFrame->set_TrimFromStart(1000.0f);

//トリミング終了時刻を2秒に設定
videoFrame->set_TrimFromEnd(2000.0f);
```

## 参照

* クラス [IVideoFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)