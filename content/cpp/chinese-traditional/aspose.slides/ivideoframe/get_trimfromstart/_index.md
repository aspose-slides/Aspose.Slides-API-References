---
title: get_TrimFromStart()
second_title: Aspose.Slides for C++ API 參考
description: 修剪起始 [ms]
type: docs
weight: 209
url: /zh-hant/aspose.slides/ivideoframe/get_trimfromstart/
---
## IVideoFrame::get_TrimFromStart() 方法


修剪起始 [ms]

```cpp
virtual float Aspose::Slides::IVideoFrame::get_TrimFromStart()=0
```

## 備註


範例： 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//設定修剪開始時間 1 秒
videoFrame->set_TrimFromStart(1000.0f);

//設定修剪結束時間 2 秒
videoFrame->set_TrimFromEnd(2000.0f);
```

## 另見

* 類別 [IVideoFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)