---
title: get_Character()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "อักขระสำเนียง ค่าต้องอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() เมธอด

Accent Character ค่าต้องอยู่ในช่วง (U+0300\\u2013U+036F) หรือ (U+20D0\\u2013U+20EF) ค่าเริ่มต้น: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
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