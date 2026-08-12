---
title: get_ColumnGapRule()
second_title: "อ้างอิง API ของ Aspose.Slides สำหรับ C++"
description: "ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น ems หรือ points (เก็บเป็น twips) ได้. ค่าเริ่มต้น: SingleSpacingGap (0)"
type: docs
weight: 105
url: /th/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() เมธอด

ประเภทของช่องว่างแนวนอนระหว่างคอลัมน์ของเมทริกซ์; หน่วยช่องว่างแนวนอนสามารถเป็น ems หรือ points (เก็บเป็น twips) ได้. ค่าเริ่มต้น: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## ดูเพิ่มเติม

* Enum [MathSpacingRules](../../mathspacingrules/)
* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)