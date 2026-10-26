---
title: set_MinColumnWidth()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: "ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ระยะห่างระหว่างคอลัมน์ (ซึ่งเรียกว่า \\u201CColumn Gap\\u201D หรือ \\u201CGap Width\\u201D) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดระยะห่างรวมของ Matrix Column Spacing (ระยะทางระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0."
type: docs
weight: 92
url: /th/aspose.slides.mathtext/mathmatrix/set_mincolumnwidth/
---
## MathMatrix::set_MinColumnWidth(uint32_t) เมธอด

ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ระยะห่างระหว่างคอลัมน์ (หรือที่เรียกว่า “Column Gap” หรือ “Gap Width”) จะถูกเพิ่มไปยัง MinColumnWidth เพื่อกำหนดค่าระยะห่างทั้งหมดของ Matrix [Column](../../../aspose.slides/column/) Spacing (ระยะทางระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0.

```cpp
void Aspose::Slides::MathText::MathMatrix::set_MinColumnWidth(uint32_t value) override
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## ดูเพิ่มเติม

* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)