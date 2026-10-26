---
title: get_CaptionTracks()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับคอลเลกชันของคำบรรยายแบบปิดที่เชื่อมโยงกับเฟรมเสียง คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและคืนค่า ICaptionsCollection ที่มีแทรกคำบรรยายทั้งหมด
type: docs
weight: 456
url: /th/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() เมธอด

รับคอลเลกชันของคำบรรยายแบบปิดที่เชื่อมโยงกับเฟรมเสียงนี้. คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../../icaptionscollection/) ที่มีแทรกคำบรรยายทั้งหมด.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
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
        // บันทึกข้อมูลไบนารีของแทรกคำบรรยายเป็นไฟล์ .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptionsCollection](../../icaptionscollection/)
* Class [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)