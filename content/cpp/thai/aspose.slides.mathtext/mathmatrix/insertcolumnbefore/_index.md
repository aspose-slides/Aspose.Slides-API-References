---
title: InsertColumnBefore()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มแรกทุกองค์ประกอบในคอลัมน์ใหม่จะเป็นค่า null.
type: docs
weight: 326
url: /th/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) method


แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มแรกทุกองค์ประกอบในคอลัมน์ใหม่จะเป็นค่า null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีของคอลัมน์ที่ต้องการแทรกคอลัมน์ใหม่ก่อน |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## ดูเพิ่มเติม

* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)