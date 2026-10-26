---
title: InsertRowAfter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทรกแถวใหม่หลังจากแถวที่ระบุ โดยค่าตั้งต้นของทุกองค์ประกอบในแถวใหม่คือ null.
type: docs
weight: 300
url: /th/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) เมธอด

แทรกแถวใหม่หลังจากแถวที่ระบุ โดยค่าตั้งต้นของทุกองค์ประกอบในแถวใหม่คือ null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| rowIndex | **int32_t** | ดัชนีของแถวที่ต้องการแทรกแถวใหม่หลังจากแถวนี้ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## ดูเพิ่มเติม

* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)