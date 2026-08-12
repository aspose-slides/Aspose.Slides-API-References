---
title: set_Sound()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงเสียงที่เล่นของไฮเปอร์ลิงค์ เขียน IAudio.
type: docs
weight: 300
url: /th/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) เมธอด


แสดงถึงเสียงที่เล่นของไฮเปอร์ลิงค์ เขียน [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// ดึงไฮเปอร์ลิงค์ของรูปร่างแรก
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // แยกเสียงของไฮเปอร์ลิงค์เป็นอาร์เรย์ของไบท์
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IAudio](../../iaudio/)
* คลาส [Hyperlink](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)