---
title: Delimit()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดขอบเขตให้กับองค์ประกอบย่อยทั้งหมดด้วยอักขระตัวคั่น (โดยไม่มีวงเล็บ)
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) เมธอด

กำหนดขอบเขตให้กับองค์ประกอบย่อยทั้งหมดด้วยอักขระตัวคั่น (โดยไม่มีวงเล็บ)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| separatorCharacter | char16_t | อักขระที่ใช้เป็นตัวคั่น |

### ค่าที่ส่งกลับ

อินสแตนซ์ของ [IMathDelimiter](../../imathdelimiter/) อิลิเมนต์

## หมายเหตุ



ตัวอย่าง:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathDelimiter](../../imathdelimiter/)
* คลาส [IMathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)