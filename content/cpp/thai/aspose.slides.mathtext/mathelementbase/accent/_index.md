---
title: Accent()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดเครื่องหมายสำเนียง (อักขระที่อยู่ด้านบนขององค์ประกอบนี้)
type: docs
weight: 196
url: /th/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) method

กำหนดเครื่องหมายสำเนียง (อักขระที่อยู่ด้านบนขององค์ประกอบนี้)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| accentCharacter | char16_t | อักขระสำเนียง ค่าควรอยู่ในช่วงของ (U+0300\u2013U+036F) หรือ (U+20D0\u2013U+20EF) |

### ค่าที่คืน

อินสแตนซ์ใหม่ของประเภท [IMathAccent](../../imathaccent/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathAccent](../../imathaccent/)
* คลาส [MathElementBase](../)
* เนมส페ซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)