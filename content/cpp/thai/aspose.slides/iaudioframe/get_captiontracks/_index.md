---
title: get_CaptionTracks()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: รับคอลเลกชันของคำบรรยายแบบปิดที่เชื่อมโยงกับเฟรมเสียง คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและส่งคืน ICaptionsCollection ที่ประกอบด้วยแทรก์คำบรรยายทั้งหมด.
type: docs
weight: 456
url: /th/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() เมธอด


รับค่าคอลเลกชันของคำบรรยายแบบปิดที่เชื่อมโยงกับเฟรมเสียง คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและส่งคืน [ICaptionsCollection](../../icaptionscollection/) ที่ประกอบด้วยแทร็กคำบรรยายทั้งหมด.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // บันทึกข้อมูลไบนารีของแทร็กคำบรรยายเป็นไฟล์ .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [ICaptionsCollection](../../icaptionscollection/)
* คลาส [IAudioFrame](../)
* เนมส페ซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)