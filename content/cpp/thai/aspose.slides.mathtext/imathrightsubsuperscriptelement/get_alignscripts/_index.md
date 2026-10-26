---
title: get_AlignScripts()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุการจัดแนวของตัวห้อย/ตัวยก. เมื่อเป็น true, ตัวห้อยและตัวยกจะจัดแนวในแนวนอนต่อกัน. เมื่อเป็น false, พวกมันจะถูกเคอร์นให้ตามรูปทรงของฐาน. ค่าเริ่มต้นคือ false.
type: docs
weight: 40
url: /th/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() เมธอด


ระบุการจัดแนวของตัวห้อย/ตัวยก. เมื่อเป็น true, ตัวห้อยและตัวยกจะจัดแนวในแนวนอนต่อกัน. เมื่อเป็น false, พวกมันจะถูกเคอร์นให้ตามรูปทรงของฐาน. ค่าปริยายคือ false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## ดูเพิ่มเติม

* คลาส [IMathRightSubSuperscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)