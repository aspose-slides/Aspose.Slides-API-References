---
title: set_TrimFromStart()
second_title: Aspose.Slides for C++ API 參考
description: 修剪開始 [ms]
type: docs
weight: 222
url: /zh-hant/aspose.slides/ivideoframe/set_trimfromstart/
---
## IVideoFrame::set_TrimFromStart(float) 方法


修剪開始 [ms]

```cpp
virtual void Aspose::Slides::IVideoFrame::set_TrimFromStart(float value)=0
```

## 備註


範例：
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//設定修剪開始時間 1秒
videoFrame->set_TrimFromStart(1000.0f);

//設定修剪結束時間 2秒
videoFrame->set_TrimFromEnd(2000.0f);
```

## 參見

* 類別 [IVideoFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)