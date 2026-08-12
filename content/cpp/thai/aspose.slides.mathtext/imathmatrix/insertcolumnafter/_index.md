---
title: InsertColumnAfter()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทรกคอลัมน์ใหม่หลังจากคอลัมน์ที่ระบุ โดยค่าเริ่มต้นทุกองค์ประกอบในคอลัมน์ใหม่จะเป็น null.
type: docs
weight: 326
url: /th/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) เมธอด

แทรกคอลัมน์ใหม่หลังจากคอลัมน์ที่ระบุ โดยค่าเริ่มต้นทุกองค์ประกอบในคอลัมน์ใหม่จะเป็น null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### อาร์กิวเมนท์

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | ดัชนีของคอลัมน์ที่ต้องการแทรกคอลัมน์ใหม่หลังจากนั้น |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## ดูเพิ่มเติม

* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)