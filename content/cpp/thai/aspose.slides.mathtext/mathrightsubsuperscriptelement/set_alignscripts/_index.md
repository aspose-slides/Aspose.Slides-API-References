---
title: set_AlignScripts()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุการจัดแนวของตัวห้อย/ตัวยก เมื่อเป็น true ตัวห้อยและตัวยกจะจัดแนวในแนวนอนต่อกัน เมื่อเป็น false จะถูกปรับระยะให้เข้ากับรูปทรงของฐาน ค่าเริ่มต้นคือ false.
type: docs
weight: 40
url: /th/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) เมธอด


ระบุการจัดแนวของตัวห้อย/ตัวยก. เมื่อเป็น true, ตัวห้อยและตัวยกจะจัดแนวในแนวนอนต่อกัน. เมื่อเป็น false, พวกมันจะถูกปรับระยะให้พอดีกับรูปทรงของฐาน. ค่าเริ่มต้นคือ false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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

* คลาส [MathRightSubSuperscriptElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)