---
title: set_GrowToMatchOperandHeight()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุการเติบโตของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นค่าจริง ตัวแบ่งจะเติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของ operand ค่าเริ่มต้นคือ true
type: docs
weight: 105
url: /th/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) เมธอด

ระบุการเติบโตของ BeginningCharacter, SeparatorCharacter, EndingCharacter เมื่อเป็นค่าจริง ตัวแบ่งจะเติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของ operand. ค่าเริ่มต้นคือ true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## ดูเพิ่มเติม

* คลาส [IMathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)