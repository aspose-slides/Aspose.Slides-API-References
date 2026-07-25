---
title: get_TrimFromStart()
second_title: Aspose.Slides for C++ API リファレンス
description: トリム開始 [ms]
type: docs
weight: 209
url: /ja/aspose.slides/ivideoframe/get_trimfromstart/
---
## IVideoFrame::get_TrimFromStart() メソッド


トリム開始 [ms]

```cpp
virtual float Aspose::Slides::IVideoFrame::get_TrimFromStart()=0
```

## 備考


例:
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//トリム開始時間を1秒に設定
videoFrame->set_TrimFromStart(1000.0f);

//トリム終了時間を2秒に設定
videoFrame->set_TrimFromEnd(2000.0f);
```

## 参照

* クラス [IVideoFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)