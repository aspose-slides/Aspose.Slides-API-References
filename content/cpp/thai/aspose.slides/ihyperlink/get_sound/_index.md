---
title: get_Sound()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แสดงเสียงที่เล่นของไฮเปอร์ลิงก์. อ่าน IAudio.
type: docs
weight: 183
url: /th/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() เมธอด


แสดงเสียงที่เล่นของไฮเปอร์ลิงก์. อ่าน [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// รับไฮเปอร์ลิงก์ของรูปทรงแรก
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // แยกข้อมูลเสียงของไฮเปอร์ลิงก์เป็นอาร์เรย์ไบต์
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## ดูเพิ่มเติม

* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudio](../../iaudio/)
* คลาส [IHyperlink](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)