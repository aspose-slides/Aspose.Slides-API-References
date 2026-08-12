---
title: set_OperatorEmulator()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ตัวจำลองโอเปอเรเตอร์ เมื่อเป็น true กล่องและเนื้อหาภายในทำงานเหมือนเป็นโอเปอเรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์ ซึ่งหมายความว่า ตัวอักษรสามารถทำหน้าที่เป็นจุดสำหรับการตัดบรรทัดและสามารถจัดแนวกับโอเปอเรเตอร์อื่น ๆ ได้ ตัวจำลองโอเปอเรเตอร์มักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็นโอเปอเรเตอร์ เช่น '==' ค่าเริ่มต้น: false"
type: docs
weight: 27
url: /th/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) method

ตัวจำลองโอเปอเรเตอร์ เมื่อเป็น true กล่องและเนื้อหาภายในทำงานเหมือนเป็นโอเปอเรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์ ซึ่งหมายความว่า ตัวอักษรสามารถทำหน้าที่เป็นจุดสำหรับการตัดบรรทัดและสามารถจัดแนวกับโอเปอเรเตอร์อื่น ๆ ได้ ตัวจำลองโอเปอเรเตอร์มักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็นโอเปอเรเตอร์ เช่น '==' ค่าเริ่มต้น: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## ดูเพิ่มเติม

* คลาส [IMathBox](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)