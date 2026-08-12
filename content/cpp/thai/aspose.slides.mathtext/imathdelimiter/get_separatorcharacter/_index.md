---
title: get_SeparatorCharacter()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "Delimiter Separator Character ระบุอักขระที่ใช้แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ delimiter. ค่าเริ่มต้น: '|'."
type: docs
weight: 40
url: /th/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() method


Delimiter Separator Character ระบุอักขระที่ใช้แยกอาร์กิวเมนต์ในอ็อบเจ็กต์ delimiter. ค่าเริ่มต้น: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## ดูเพิ่มเติม

* คลาส [IMathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)