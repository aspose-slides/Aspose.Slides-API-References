---
title: idx_set()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: องค์ประกอบของเมทริกซ์
type: docs
weight: 222
url: /th/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) เมธอด

องค์ประกอบของเมทริกซ์

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| row | **int32_t** | ดัชนีเริ่มจากศูนย์ของแถวเพื่อรับรายการ |
| column | **int32_t** | ดัชนีเริ่มจากศูนย์ของคอลัมน์เพื่อรับรายการ |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## Remarks

ตัวอย่าง:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathMatrix](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)