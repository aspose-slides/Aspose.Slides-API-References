---
title: idx_set()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่วนประกอบของเมทริกซ์
type: docs
weight: 222
url: /th/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) เมธอด

ส่วนประกอบของเมทริกซ์

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| row | **int32_t** | ดัชนีที่เริ่มจากศูนย์ของแถวเพื่อรับรายการ |
| column | **int32_t** | ดัชนีที่เริ่มจากศูนย์ของคอลัมน์เพื่อรับรายการ |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)