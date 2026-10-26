---
title: set_Character()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "อักขระสำเนียง ค่าควรอยู่ในช่วงของ (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) ค่าตั้งต้น: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /th/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) เมธอด


อักขระสำเนียง ค่าที่ควรอยู่ในช่วงของ (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าตั้งต้น: Combining Circumflex Accent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## หมายเหตุ


ตัวอย่าง:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## ดูเพิ่มเติม

* คลาส [MathAccent](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)