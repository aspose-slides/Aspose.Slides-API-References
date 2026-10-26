---
title: get_AlignScripts()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุการจัดแนวของตัวห้อย/ตัวเอื้ยง เมื่อเป็น true ตัวห้อยและตัวเอื้ยงจะจัดแนวแนวนอนต่อกัน เมื่อเป็น false พวกมันจะเคอร์นให้เข้ากับรูปร่างของฐาน ค่าเริ่มต้นคือ false.
type: docs
weight: 27
url: /th/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() เมธอด

ระบุการจัดแนวของตัวห้อย/ตัวเอื้ยง เมื่อเป็น true ตัวห้อยและตัวเอื้ยงจะจัดแนวแนวนอนต่อกัน เมื่อเป็น false พวกมันจะเคอร์นให้เข้ากับรูปร่างของฐาน ค่าเริ่มต้นคือ false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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