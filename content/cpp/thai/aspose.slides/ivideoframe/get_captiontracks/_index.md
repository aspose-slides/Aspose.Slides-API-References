---
title: get_CaptionTracks()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงชุดข้อมูลของคำบรรยายปิดที่เชื่อมโยงกับกรอบเสียง คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและคืนค่า ICaptionsCollection ที่มีแทร็กคำบรรยายทั้งหมด.
type: docs
weight: 261
url: /th/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() เมธอด

ดึงชุดข้อมูลของคำบรรยายปิดที่เชื่อมโยงกับกรอบเสียง คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../../icaptionscollection/) ที่มีแทร็กคำบรรยายทั้งหมด.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## หมายเหตุ

ตัวอย่าง: 
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
        // ดึงข้อมูลไบนารีของคำบรรยายและบันทึกลงไฟล์
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ICaptionsCollection](../../icaptionscollection/)
* คลาส [IVideoFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)