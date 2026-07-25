---
title: set_TrimFromStart()
second_title: Aspose.Slides の C++ API リファレンス
description: 開始トリム [ms]
type: docs
weight: 222
url: /ja/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) メソッド


開始トリム [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## 備考


例: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//開始トリミング時間を1秒に設定
videoFrame->set_TrimFromStart(1000.0f);

//終了トリミング時間を2秒に設定
videoFrame->set_TrimFromEnd(2000.0f);
```

## 関連項目

* クラス [VideoFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)