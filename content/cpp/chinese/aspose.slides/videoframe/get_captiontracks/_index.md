---
title: get_CaptionTracks()
second_title: Aspose.Slides C++ API 参考
description: 获取与视频帧关联的隐藏字幕集合。此属性为只读，并返回一个 ICaptionsCollection，其中包含所有字幕轨道。
type: docs
weight: 261
url: /zh/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() 方法

获取与视频帧关联的隐藏字幕集合。此属性为只读，并返回一个 [ICaptionsCollection](../../icaptionscollection/)，其中包含所有字幕轨道。

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
```

## 备注


示例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"video with captions.pptx");

for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    System::SharedPtr<IVideoFrame> videoFrame = System::AsCast<IVideoFrame>(shape);
    if (videoFrame != nullptr)
    {
        continue;
    }

    for (auto&& captionTrack : videoFrame->get_CaptionTracks())
    {
        // 提取字幕二进制数据并保存到文件
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ICaptionsCollection](../../icaptionscollection/)
* 类 [VideoFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)