---
title: SetColumnsAlignment()
second_title: Aspose.Slides برای C++ مرجع API
description: تراز افقی ستون‌های مشخص‌شده را تنظیم کنید
type: docs
weight: 274
url: /fa/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) متد

تراز افقی ستون‌های مشخص‌شده را تنظیم کنید

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | اندیس صفر-مبنا برای اولین ستونی که تراز آن تنظیم می‌شود |
| columnsCount | **uint32_t** | تعداد ستون‌هایی که تراز آنها باید مشخص شود |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | مقدار جدید تراز افقی ستون مشخص شده |

## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## همچنین ببینید

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)