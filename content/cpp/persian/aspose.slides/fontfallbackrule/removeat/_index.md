---
title: RemoveAt()
second_title: مرجع API Aspose.Slides برای C++ 
description: قلم FallBack را در اندیس مشخص‌شدهٔ فهرست حذف می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) متد

قلم FallBack را در اندیس مشخص‌شدهٔ فهرست حذف می‌کند.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر-پایهٔ قلمی که باید حذف شود. |

## توضیحات

```cpp
// یک قانون ایجاد می‌کند که شامل فهرستی از قلم‌ها است.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//حذف Tahoma از فهرست.
newRule->RemoveAt(2);
```

## برای اطلاعات بیشتر

* کلاس [FontFallBackRule](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)