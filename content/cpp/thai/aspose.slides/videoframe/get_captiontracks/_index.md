---
title: get_CaptionTracks()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับคอลเลกชันของคำบรรยายปิดที่เกี่ยวข้องกับเฟรมวิดีโอ. คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและคืนค่า ICaptionsCollection ที่ประกอบด้วยแทร็กคำบรรยายทั้งหมด.
type: docs
weight: 261
url: /th/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() เมธอด

รับคอลเลกชันของคำบรรยายปิดที่เกี่ยวข้องกับเฟรมวิดีโอ คุณสมบัตินี้อ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../../icaptionscollection/) ที่ประกอบด้วยแทร็กคำบรรยายทั้งหมด

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
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
* คลาส [VideoFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)