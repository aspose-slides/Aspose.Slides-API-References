---
title: get_ColumnGap()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งค่าเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ตั้งค่าเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่นจะถูกละเว้น. ค่าเริ่มต้น: 0"
type: docs
weight: 131
url: /th/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() เมธอด

เป็นค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ตั้งเป็นค่า 3 ("Exactly"), หน่วยจะถูกตีความเป็น twips (1/20 ของ point) หาก ColumnGapRule ตั้งเป็นค่า 4 ("Multiple"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่น ๆ จะถูกละเว้น. ค่าเริ่มต้น: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## ดูเพิ่มเติม

* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)