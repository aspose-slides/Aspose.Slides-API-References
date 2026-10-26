---
title: set_ColumnGap()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ค่าของช่องว่างตามแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ถูกตั้งค่าเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ถูกตั้งค่าเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่นจะถูกละเลย. ค่าเริ่มต้น: 0"
type: docs
weight: 144
url: /th/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) เมธอด


ค่าของช่องว่างตามแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งค่าเป็น 3 ("Exactly"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งค่าเป็น 4 ("Multiple"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่นจะถูกละเว้น ค่าเริ่มต้น: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## ดูเพิ่มเติม

* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)