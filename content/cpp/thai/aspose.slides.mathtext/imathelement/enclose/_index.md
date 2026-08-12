---
title: Enclose()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ใส่วงเล็บรอบองค์ประกอบคณิตศาสตร์
type: docs
weight: 40
url: /th/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() เมธอด

ใส่วงเล็บรอบองค์ประกอบคณิตศาสตร์

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### ค่าที่คืนกลับ

องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../imathdelimiter/) ซึ่งรวมวงเล็บไว้

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) เมธอด

ใส่วงเล็บหรืออักขระอื่นตามที่ระบุรอบองค์ประกอบนี้

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char16_t | อักขระเริ่มต้น (โดยทั่วไปเป็นวงเล็บซ้าย) |
| endingCharacter | char16_t | อักขระสิ้นสุด (โดยทั่วไปเป็นวงเล็บขวา) |

### ค่าที่คืนกลับ

องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../imathdelimiter/) ซึ่งรวมอักขระที่ระบุไว้เป็นกรอบ

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)