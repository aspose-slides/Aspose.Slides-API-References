---
title: get_Sound()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์. อ่าน IAudio.
type: docs
weight: 287
url: /th/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() เมธอด

แสดงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์. อ่าน [IAudio](../../iaudio/).

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
```

## หมายเหตุ


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// รับไฮเปอร์ลิงก์ของรูปร่างแรก
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // ดึงข้อมูลเสียงของไฮเปอร์ลิงก์เป็นอาร์เรย์ของไบต์
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudio](../../iaudio/)
* คลาส [Hyperlink](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)