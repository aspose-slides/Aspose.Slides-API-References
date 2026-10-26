---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API 參考
description: 取得與音訊框架相關聯的隱藏字幕集合。此屬性為唯讀，並回傳一個 ICaptionsCollection，其中包含所有字幕軌道。
type: docs
weight: 456
url: /zh-hant/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() 方法


取得與音訊框架相關聯的隱藏字幕集合。此屬性為唯讀，並回傳一個 [ICaptionsCollection](../../icaptionscollection/)，其中包含所有字幕軌道。

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
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

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ICaptionsCollection](../../icaptionscollection/)
* 類別 [IAudioFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)