---
title: set_AlignScripts()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดการจัดแนวของตัวห้อยบน/ตัวห้อยล่าง เมื่อค่าเป็น true ตัวห้อยล่างและตัวห้อยบนจะจัดแนวแนวนอนกัน เมื่อค่าเป็น false จะจัดให้เข้ากับรูปร่างของฐาน ค่าเริ่มต้นคือ false.
type: docs
weight: 53
url: /th/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) method


กำหนดการจัดแนวของตัวห้อยบน/ตัวห้อยล่าง เมื่อค่าเป็น true ตัวห้อยล่างและตัวห้อยบนจะจัดแนวแนวนอนกัน เมื่อค่าเป็น false จะจัดให้เข้ารูปร่างของฐาน ค่าเริ่มต้นคือ false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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