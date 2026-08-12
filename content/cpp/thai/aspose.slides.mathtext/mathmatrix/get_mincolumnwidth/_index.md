---
title: get_MinColumnWidth()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ความกว้างคอลัมน์ต่ำสุดใน twips (1/20 ของจุด) ช่องว่างระหว่างคอลัมน์ (ยังเรียกว่า \\u201CColumn Gap\\u201D หรือ \\u201CGap Width\\u201D) จะถูกเพิ่มไปที่ MinColumnWidth เพื่อกำหนดค่า Matrix Column Spacing ทั้งหมด (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0."
type: docs
weight: 79
url: /th/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() เมธอด

ความกว้างคอลัมน์ต่ำสุดใน twips (1/20th of a point) ช่องว่างระหว่างคอลัมน์ (also referred to as \\u201CColumn Gap\\u201D หรือ \\u201CGap Width\\u201D) ถูกเพิ่มไปที่ MinColumnWidth เพื่อกำหนดค่า Matrix [Column](../../../aspose.slides/column/) Spacing (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ต่าง ๆ) ค่าเริ่มต้น: 0.

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
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