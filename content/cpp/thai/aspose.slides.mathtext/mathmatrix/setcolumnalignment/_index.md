---
title: SetColumnAlignment()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ
type: docs
weight: 261
url: /th/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) เมธอด

ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีคอลัมน์ตั้งแต่ศูนย์ |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | ค่าใหม่ของการจัดแนวนอนของคอลัมน์ที่ระบุ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## ดูเพิ่มเติม

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)