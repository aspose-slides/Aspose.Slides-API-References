---
title: get_CaptionTracks()
second_title: Aspose.Slides C++ API 参考
description: 获取与音频帧关联的闭合字幕集合。此属性为只读，并返回一个 ICaptionsCollection，包含所有字幕轨道。
type: docs
weight: 456
url: /zh/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() 方法

获取与音频帧关联的闭合字幕集合。此属性为只读，并返回一个 [ICaptionsCollection](../../icaptionscollection/)，其中包含所有字幕轨道。

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## 备注

示例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // 将字幕轨道的二进制数据保存为 .vtt 文件
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ICaptionsCollection](../../icaptionscollection/)
* 类 [IAudioFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)