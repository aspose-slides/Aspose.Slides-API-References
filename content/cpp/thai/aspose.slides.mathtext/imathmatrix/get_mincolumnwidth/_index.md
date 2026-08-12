---
title: get_MinColumnWidth()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides for C++
description: "ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ช่องว่างระยะห่าง (ซึ่งเรียกอีกอย่างว่า \\u201CColumn Gap\\u201D หรือ \\u201CGap Width\\u201D) จะถูกเพิ่มเข้าไปที่ MinColumnWidth เพื่อกำหนดค่า Matrix Column Spacing (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ที่ต่างกัน) ค่าเริ่มต้น: 0."
type: docs
weight: 79
url: /th/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() เมธอด

ความกว้างคอลัมน์ขั้นต่ำใน twips (1/20 ของจุด) ช่องว่างระยะห่าง (also referred to as “Column Gap” หรือ “Gap Width”) จะถูกเพิ่มเข้าไปที่ MinColumnWidth เพื่อกำหนดค่า Matrix [Column](../../../aspose.slides/column/) Spacing (ระยะห่างระหว่างขอบเดียวกันของคอลัมน์ที่ต่างกัน) ค่าเริ่มต้น: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
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