---
title: idx_get()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่วนประกอบของเมทริกซ์
type: docs
weight: 209
url: /th/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) เมธอด

ส่วนประกอบของเมทริกซ์

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| row | **int32_t** | ดัชนีเริ่มจากศูนย์ของ row เพื่อรับรายการ |
| column | **int32_t** | ดัชนีเริ่มจากศูนย์ของ column เพื่อรับรายการ |

### ค่าที่ส่งคืน


## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## ดูเพิ่มเติม

* พิมพ์นิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)