---
title: InsertColumnBefore()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มแรกทุกองค์ประกอบในคอลัมน์ใหม่จะเป็นค่า null.
type: docs
weight: 313
url: /th/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) เมธอด

แทรกคอลัมน์ใหม่ก่อนคอลัมน์ที่ระบุ โดยเริ่มแรกทุกองค์ประกอบในคอลัมน์ใหม่จะเป็นค่า null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีของคอลัมน์ที่จะแทรกคอลัมน์ใหม่ก่อน |

## หมายเหตุ

ตัวอย่าง:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## ดูเพิ่มเติม

* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)