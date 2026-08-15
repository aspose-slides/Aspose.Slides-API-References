---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API 參考
description: 取得與影片框架相關的隱閉字幕集合。此屬性為唯讀，並回傳一個 ICaptionsCollection，包含所有字幕軌道。
type: docs
weight: 261
url: /zh-hant/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() method


取得與影片框架相關的隱閉字幕集合。此屬性為唯讀，並回傳一個 [ICaptionsCollection](../../icaptionscollection/)，其中包含所有字幕軌道。

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
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

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ICaptionsCollection](../../icaptionscollection/)
* 類別 [VideoFrame](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)