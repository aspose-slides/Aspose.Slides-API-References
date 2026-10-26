---
title: set_RowGap()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ค่าการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ตั้งค่าเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ตั้งค่าเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นครึ่งบรรทัด. ค่าเริ่มต้น: 0"
type: docs
weight: 196
url: /th/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) method

ค่าการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ถูกตั้งค่าเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ถูกตั้งค่าเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นครึ่งบรรทัด. ค่าเริ่มต้น: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## ดูเพิ่มเติม

* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)