---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API 參考
description: 取得與音訊框架相關聯的隱藏字幕集合。此屬性為唯讀，回傳一個包含所有字幕軌道的 ICaptionsCollection。
type: docs
weight: 261
url: /zh-hant/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() 方法

取得與音訊框架相關聯的隱藏字幕集合。此屬性為唯讀，回傳一個包含所有字幕軌道的 [ICaptionsCollection](../../icaptionscollection/)。

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## 備註

範例：
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
        // 提取字幕的二進位資料並將其儲存到檔案
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ICaptionsCollection](../../icaptionscollection/)
* 類別 [IVideoFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)