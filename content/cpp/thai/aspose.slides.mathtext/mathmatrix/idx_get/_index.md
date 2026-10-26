---
title: idx_get()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: องค์ประกอบของเมทริกซ์
type: docs
weight: 209
url: /th/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) เมธอด


องค์ประกอบของเมทริกซ์

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| row | **int32_t** | ดัชนีเริ่มจากศูนย์ของแถวเพื่อดึงรายการ |
| column | **int32_t** | ดัชนีเริ่มจากศูนย์ของคอลัมน์เพื่อดึงรายการ |

### ค่าที่คืน


## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)