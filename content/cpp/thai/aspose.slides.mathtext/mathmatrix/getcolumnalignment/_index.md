---
title: GetColumnAlignment()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับการจัดแนวนอนของคอลัมน์ที่ระบุ
type: docs
weight: 248
url: /th/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) เมธอด

รับการจัดแนวนอนของคอลัมน์ที่ระบุ

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีคอลัมน์เริ่มจากศูนย์ |

### ค่าที่ส่งกลับ

การจัดแนวนอนของคอลัมน์ที่ระบุ
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## ดูเพิ่มเติม

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)