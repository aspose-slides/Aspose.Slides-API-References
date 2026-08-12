---
title: set_RowGap()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ค่าการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ถูกตั้งค่าเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20th of a point) หาก RowGapRule ถูกตั้งค่าเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines. ค่าเริ่มต้น: 0"
type: docs
weight: 196
url: /th/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) เมธอด


ค่าของการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ถูกตั้งค่าเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20th of a point) หาก RowGapRule ถูกตั้งค่าเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็น half-lines. ค่าเริ่มต้น: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## ดูเพิ่มเติม

* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)