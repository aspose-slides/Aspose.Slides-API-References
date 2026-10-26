---
title: set_ColumnGap()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ค่าการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ถูกตั้งค่าเป็น 3 (\"Exactly\"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ถูกตั้งค่าเป็น 4 (\"Multiple\"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่นจะถูกละเว้น. ค่าเริ่มต้น: 0"
type: docs
weight: 144
url: /th/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) เมธอด

ค่าของการเว้นระยะแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หาก ColumnGapRule ถูกตั้งค่าเป็น 3 ("Exactly"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก ColumnGapRule ถูกตั้งค่าเป็น 4 ("Multiple"), หน่วยจะถูกตีความเป็นจำนวนของการเพิ่ม 0.5 em. ในกรณีอื่น ๆ จะถูกละเว้น. ค่าเริ่มต้น: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
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