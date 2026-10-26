---
title: get_RowGap()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ค่าการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ถูกตั้งเป็น 3 (\"Exactly\"), หน่วยจะตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ถูกตั้งเป็น 4 (\"Multiple\"), หน่วยจะตีความเป็นครึ่งบรรทัด. ค่าเริ่มต้น: 0"
type: docs
weight: 183
url: /th/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() เมธอด


ค่าการเว้นระยะแนวตั้งระหว่างแถวของเมทริกซ์; หาก RowGapRule ถูกตั้งค่าเป็น 3 ("Exactly"), หน่วยจะถูกตีความเป็น twips (1/20 ของจุด) หาก RowGapRule ถูกตั้งค่าเป็น 4 ("Multiple"), หน่วยจะถูกตีความเป็นครึ่งบรรทัด. ค่าเริ่มต้น: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
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