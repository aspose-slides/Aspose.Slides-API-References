---
title: Delimit()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: แยกอาร์กิวเมนต์โดยใช้ตัวอักษรตัวคั่นที่ระบุ
type: docs
weight: 144
url: /th/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) เมธอด

แยกอาร์กิวเมนต์โดยใช้ตัวอักษรตัวคั่นที่ระบุ

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| separatorCharacter | char16_t | ตัวอักษรตัวคั่น |

### ค่าที่ส่งกลับ

อ็อบเจกต์นี้หลังจากนำตัวอักษรตัวคั่นไปใช้
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)