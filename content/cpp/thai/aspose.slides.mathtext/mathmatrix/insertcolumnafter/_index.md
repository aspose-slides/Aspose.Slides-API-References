---
title: InsertColumnAfter()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ โดยเริ่มต้นสมาชิกทั้งหมดในคอลัมน์ใหม่จะเป็นค่า null.
type: docs
weight: 339
url: /th/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) เมธอด

แทรกคอลัมน์ใหม่หลังคอลัมน์ที่ระบุ โดยเริ่มต้นสมาชิกทั้งหมดในคอลัมน์ใหม่จะเป็นค่า null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีของคอลัมน์ที่ต้องการแทรกคอลัมน์ใหม่หลังจากนั้น |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## ดูเพิ่มเติม

* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)