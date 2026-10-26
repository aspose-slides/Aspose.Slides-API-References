---
title: InsertRowAfter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทรกแถวใหม่หลังจากแถวที่ระบุ โดยเริ่มต้นทุกองค์ประกอบในแถวใหม่จะเป็นค่า null.
type: docs
weight: 287
url: /th/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) เมธอด

Insert a new row after the specified one Initially all elements in the new row are null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | Index of the row after which to insert a new one |

## หมายเหตุ



ตัวอย่าง:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## ดูเพิ่มเติม

* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)