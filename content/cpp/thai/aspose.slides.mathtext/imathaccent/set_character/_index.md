---
title: set_Character()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "อักขระสำเนียง ค่าต้องอยู่ในช่วงของ (U+0300\\u2013U+036F) หรือ(U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /th/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) เมธอด

อักขระสำเนียง ค่าควรอยู่ในช่วงของ (U+0300\\u2013U+036F) หรือ(U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## ดูเพิ่มเติม

* คลาส [IMathAccent](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)