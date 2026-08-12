---
title: GetColumnAlignment()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: รับการจัดตำแหน่งแนวนอนของคอลัมน์ที่ระบุ
type: docs
weight: 235
url: /th/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) method

รับการจัดตำแหน่งแนวนอนของคอลัมน์ที่ระบุ

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีคอลัมน์ที่เริ่มจากศูนย์ |

### Return Value

การจัดตำแหน่งแนวนอนของคอลัมน์ที่ระบุ
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## ดูเพิ่มเติม

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)