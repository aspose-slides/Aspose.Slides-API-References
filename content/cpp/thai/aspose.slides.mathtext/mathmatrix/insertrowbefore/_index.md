---
title: InsertRowBefore()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทรกแถวใหม่ก่อนแถวที่กำหนด โดยเริ่มแรกทุกองค์ประกอบในแถวใหม่จะเป็นค่า null.
type: docs
weight: 287
url: /th/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) เมธอด

แทรกแถวใหม่ก่อนแถวที่กำหนด เริ่มแรกทุกองค์ประกอบในแถวใหม่จะเป็นค่า null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | ดัชนีของแถวที่ต้องการแทรกแถวใหม่ก่อนหน้า |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## ดูเพิ่มเติม

* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)