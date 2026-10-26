---
title: SetColumnAlignment()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดการจัดแนวนอนของคอลัมน์ที่ระบุ
type: docs
weight: 248
url: /th/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) เมธอด


ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีคอลัมน์ที่เริ่มจากศูนย์ |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | ค่ามูลค่าใหม่ของการจัดแนวนอนของคอลัมน์ที่ระบุ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## ดูเพิ่มเติม

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)