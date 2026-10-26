---
title: SetColumnsAlignment()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตั้งค่าการจัดเรียงแนวนอนของคอลัมน์ที่ระบุ
type: docs
weight: 274
url: /th/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) เมธอด


ตั้งค่าการจัดเรียงแนวนอนของคอลัมน์ที่ระบุ

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีที่เริ่มจากศูนย์ของคอลัมน์แรกที่ตั้งค่าการจัดเรียง |
| columnsCount | **uint32_t** | จำนวนคอลัมน์ที่ต้องการระบุการจัดเรียง |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | ค่าการจัดเรียงแนวนอนใหม่ของคอลัมน์ที่ระบุ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## ดูเพิ่มเติม

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)