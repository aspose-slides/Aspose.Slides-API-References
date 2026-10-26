---
title: get_CaptionTracks()
second_title: Aspose.Slides C++ API 参考
description: 获取与音频帧关联的闭合字幕集合。此属性为只读，并返回一个 ICaptionsCollection，包含所有字幕轨道。
type: docs
weight: 261
url: /zh/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() 方法


获取与音频帧关联的闭合字幕集合。此属性为只读，并返回一个 [ICaptionsCollection](../../icaptionscollection/)，其中包含所有字幕轨道。

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
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

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ICaptionsCollection](../../icaptionscollection/)
* 类 [IVideoFrame](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)