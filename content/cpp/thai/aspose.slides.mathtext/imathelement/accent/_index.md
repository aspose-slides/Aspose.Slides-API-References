---
title: Accent()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งเครื่องหมายสำเนียง (อักขระที่อยู่ด้านบนขององค์ประกอบนี้)
type: docs
weight: 209
url: /th/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) เมธอด

ตั้งเครื่องหมายสำเนียง (อักขระที่อยู่ด้านบนขององค์ประกอบนี้)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| accentCharacter | char16_t | อักขระสำเนียง. ค่าต้องอยู่ในช่วง (U+0300\u2013U+036F) หรือ (U+20D0\u2013U+20EF) |

## ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของประเภท [IMathAccent](../../imathaccent/)

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathAccent](../../imathaccent/)
* คลาส [IMathElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)