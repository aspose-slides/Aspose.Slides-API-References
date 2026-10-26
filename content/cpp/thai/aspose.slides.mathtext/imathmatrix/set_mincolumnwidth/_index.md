---
title: set_MinColumnWidth()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: "ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ระยะห่างช่องว่าง (ยังเรียกว่า \\u201CColumn Gap\\u201D หรือ \\u201CGap Width\\u201D) จะถูกเพิ่มเข้าไปใน MinColumnWidth เพื่อกำหนดค่า Matrix Column Spacing (ระยะทางระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0."
type: docs
weight: 92
url: /th/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) เมธอด


ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ระยะห่างของช่องว่าง (ซึ่งยังเรียกว่า \\u201CColumn Gap\\u201D หรือ \\u201CGap Width\\u201D) ถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดค่า Matrix [Column](../../../aspose.slides/column/) Spacing (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## ดูเพิ่มเติม

* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)