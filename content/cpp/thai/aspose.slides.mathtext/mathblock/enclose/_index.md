---
title: Enclose()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ห่อหุ้มองค์ประกอบลูกของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ
type: docs
weight: 222
url: /th/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) เมธอด

ห่อหุ้มองค์ประกอบลูกของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบ

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ประเภท [IMathDelimiter](../../imathdelimiter/) ที่รวมอักขระที่ระบุเป็นกรอบ
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) เมธอด


ห่อหุ้มองค์ประกอบลูกของบล็อกนี้ด้วยอักขระที่ระบุ เช่น วงเล็บหรืออักขระอื่นเป็นกรอบและคั่นด้วยอักขระตัวแบ่ง

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |
| separatorCharacter | char16_t | Separator character |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ประเภท [IMathDelimiter](../../imathdelimiter/) ที่รวมอักขระที่ระบุเป็นกรอบและตัวคั่น
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathDelimiter](../../imathdelimiter/)
* คลาส [MathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)