---
title: get_ColumnGap()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ค่าระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ถูกตั้งค่าเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ถูกตั้งค่าเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่น ๆ จะถูกละเว้น. ค่าเริ่มต้น: 0"
type: docs
weight: 131
url: /th/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() เมธอด

ค่าระยะห่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ถูกตั้งค่าเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของพอยต์) หาก ColumnGapRule ถูกตั้งค่าเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่น ๆ จะถูกละเว้น. ค่าเริ่มต้น: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
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