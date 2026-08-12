---
title: Enclose()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: บรรจุองค์ประกอบคณิตศาสตร์ในอักขระที่ระบุ เช่น วงเล็บ หรืออักขระอื่นเป็นกรอบ
type: docs
weight: 170
url: /th/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) เมธอด


บรรจุองค์ประกอบคณิตศาสตร์ในอักขระที่ระบุเช่นวงเล็บหรืออักขระอื่นเป็นกรอบ

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char16_t | อักขระเริ่มต้น (โดยปกติเป็นวงเล็บซ้าย) |
| endingCharacter | char16_t | อักขระสิ้นสุด (โดยปกติเป็นวงเล็บขวา) |

### ค่าที่คืน

หาก *beginningCharacter* และ *endingCharacter* เป็นค่า null คุณสมบัติที่สอดคล้องกันจะถูกกำหนดค่าเท่านั้นและไม่มีการสร้างอ็อบเจกต์ใหม่ (คืนค่าตัวอย่างนี้) มิฉะนั้นจะคืนองค์ประกอบคณิตศาสตร์ใหม่ประเภท Delimiter ที่รวมอักขระที่ระบุเป็นกรอบและตัวอย่างนี้ของ [MathDelimiter](../) ที่อยู่ภายในกรอบ

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathDelimiter](../../imathdelimiter/)
* คลาส [MathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)