---
title: set_Sound()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์ เขียน IAudio.
type: docs
weight: 196
url: /th/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) เมธอด

แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์. เขียน [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// รับไฮเปอร์ลิงก์ของรูปแบบแรก
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // ดึงเสียงไฮเปอร์ลิงก์เป็นอาร์เรย์ไบต์
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```




## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudio](../../iaudio/)
* คลาส [IHyperlink](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)