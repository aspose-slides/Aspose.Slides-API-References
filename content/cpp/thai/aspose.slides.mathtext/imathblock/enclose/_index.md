---
title: Enclose()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ห่อหุ้มองค์ประกอบลูกของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบและคั่นด้วยอักขระแยก
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) เมธอด


ทำการห่อหุ้มองค์ประกอบลูกของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบและคั่นด้วยอักขระแยก

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char16_t | อักขระเริ่มต้น (ส่วนใหญ่เป็นวงเล็บซ้าย) |
| endingCharacter | char16_t | อักขระสิ้นสุด (ส่วนใหญ่เป็นวงเล็บขวา) |
| separatorCharacter | char16_t | อักขระแยก |

### ค่าที่คืน

องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../imathdelimiter/) ที่รวมอักขระที่ระบุเป็นกรอบและตัวคั่น
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## ดูเพิ่มเติม

* การกำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathDelimiter](../../imathdelimiter/)
* คลาส [IMathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)