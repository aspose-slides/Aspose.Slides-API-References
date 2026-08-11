---
title: IndexOf()
second_title: مرجع API Aspose.Slides برای C++
description: یک اندیس از قاعده مشخص شده در مجموعه برمی‌گرداند.
type: docs
weight: 118
url: /fa/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) متد

یک اندیس از قاعده مشخص شده در مجموعه برمی‌گرداند.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | نام قلم برای جستجو. |

### مقدار بازگشتی

اندیس یک قلم یا -1 اگر قلم در فهرست یافت نشود.

## توضیحات

```cpp
// یک قاعده ایجاد می‌کند که شامل لیستی از قلم‌ها است.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// دریافت اندیس Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [IFontFallBackRule](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)