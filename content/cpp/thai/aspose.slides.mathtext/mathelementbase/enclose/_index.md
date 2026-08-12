---
title: Enclose()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ใส่อิลิเมนต์คณิตศาสตร์ในวงเล็บ
type: docs
weight: 27
url: /th/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() เมธอด


แทรกอิลิเมนต์คณิตศาสตร์ในวงเล็บ

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### ค่าที่ส่งคืน

อิลิเมนต์คณิตศาสตร์ประเภท [IMathDelimiter](../../imathdelimiter/) ที่รวมวงเล็บ
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) เมธอด


แทรกอิลิเมนต์คณิตศาสตร์ในอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char16_t | อักขระเริ่มต้น (โดยทั่วไปคือวงเล็บซ้าย) |
| endingCharacter | char16_t | อักขระสิ้นสุด (โดยทั่วไปคือวงเล็บขวา) |

### ค่าที่ส่งคืน

อิลิเมนต์คณิตศาสตร์ประเภท [IMathDelimiter](../../imathdelimiter/) ที่รวมอักขระที่ระบุเป็นกรอบ
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)