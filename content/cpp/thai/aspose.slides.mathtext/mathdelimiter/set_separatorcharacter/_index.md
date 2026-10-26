---
title: set_SeparatorCharacter()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "Delimiter Separator Character ระบุอักขระที่ใช้แยกอาร์กิวเมนต์ในวัตถุ delimiter. ค่าเริ่มต้น: '|'."
type: docs
weight: 53
url: /th/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) เมธอด

Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## ดูเพิ่มเติม

* คลาส [MathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)