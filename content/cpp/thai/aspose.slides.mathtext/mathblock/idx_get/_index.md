---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึง IMathElement ที่ตำแหน่งดัชนีที่ระบุ.
type: docs
weight: 27
url: /th/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) เมธอด

ดึง [IMathElement](../../imathelement/) ที่ตำแหน่งที่ระบุ

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ตำแหน่งดัชนีตั้งแต่ศูนย์ของรายการ |

### ค่าที่ส่งกลับ

องค์ประกอบคณิตศาสตร์

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBlock](../)
* เนมสเปส [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)