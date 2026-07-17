---
title: set_TrimFromStart()
second_title: Aspose.Slides C++ API 参考
description: 修剪起始 [ms]
type: docs
weight: 222
url: /zh/aspose.slides/videoframe/set_trimfromstart/
---
## VideoFrame::set_TrimFromStart(float) 方法

修剪起始 [ms]

```cpp
void Aspose::Slides::VideoFrame::set_TrimFromStart(float value) override
```

## 备注

示例：
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//设置剪辑起始时间 1秒
videoFrame->set_TrimFromStart(1000.0f);

//设置剪辑结束时间 2秒
videoFrame->set_TrimFromEnd(2000.0f);
```

## 另见

* 类 [VideoFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)