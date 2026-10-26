---
title: SetColumnsAlignment()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ
type: docs
weight: 261
url: /th/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) เมธอด

ตั้งค่าการจัดแนวนอนของคอลัมน์ที่ระบุ

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีเริ่มจากศูนย์ของคอลัมน์แรกที่ต้องตั้งค่าการจัดแนว |
| columnsCount | **uint32_t** | จำนวนคอลัมน์ที่ต้องกำหนดการจัดแนว |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | ค่าใหม่ของการจัดแนวนอนของคอลัมน์ที่ระบุ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## ดูเพิ่มเติม

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)