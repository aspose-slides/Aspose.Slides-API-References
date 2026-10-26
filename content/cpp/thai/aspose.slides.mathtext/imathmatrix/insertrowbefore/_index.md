---
title: InsertRowBefore()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกแถวใหม่ก่อนแถวที่ระบุ โดยสมาชิกทั้งหมดในแถวใหม่จะเป็นค่า null.
type: docs
weight: 274
url: /th/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) เมธอด


Insert a new row before the specified one Initially all elements in the new row are null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| rowIndex | **int32_t** | Index of the row before which to insert a new one |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## ดูเพิ่มเติม

* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)