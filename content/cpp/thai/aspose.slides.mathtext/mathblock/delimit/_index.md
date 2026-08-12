---
title: Delimit()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แยกส่วนองค์ประกอบย่อยด้วยอักขระตัวคั่น (โดยไม่มีวงเล็บ)
type: docs
weight: 209
url: /th/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) เมธอด

แยกองค์ประกอบย่อยด้วยตัวอักษรคั่น (โดยไม่มีวงเล็บ)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| separatorCharacter | char16_t | ตัวอักษรคั่น |

### ค่าที่ส่งคืน

องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../imathdelimiter/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)