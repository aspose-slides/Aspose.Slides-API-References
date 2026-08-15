---
title: get_CaptionTracks()
second_title: Aspose.Slides 的 C++ API 參考
description: 取得與音訊框架相關聯的閉合字幕集合。此屬性為唯讀，並返回一個 ICaptionsCollection，該集合包含所有字幕軌道。
type: docs
weight: 456
url: /zh-hant/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() 方法

取得與音訊框架相關聯的閉合字幕集合。此屬性為唯讀，且返回一個 [ICaptionsCollection](../../icaptionscollection/)，其中包含所有字幕軌道。

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // 將字幕軌道的二進位資料儲存為 .vtt 檔案
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ICaptionsCollection](../../icaptionscollection/)
* 類別 [AudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)