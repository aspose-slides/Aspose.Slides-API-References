---
title: get_SeparatorCharacter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "Delimiter Separator Character ระบุอักขระที่ใช้คั่นอาร์กิวเมนต์ในอ็อบเจกต์ delimiter. ค่าเริ่มต้นคือ '|'."
type: docs
weight: 40
url: /th/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() เมธอด


Delimiter Separator Character ระบุอักขระที่ใช้คั่นอาร์กิวเมนต์ในอ็อบเจกต์ delimiter. ค่าเริ่มต้นคือ '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## ดูเพิ่มเติม

* คลาส [MathDelimiter](../)
* เนมส페ซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)