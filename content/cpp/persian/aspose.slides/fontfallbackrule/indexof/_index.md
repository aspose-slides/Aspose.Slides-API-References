---
title: IndexOf()
second_title: Aspose.Slides برای مرجع API C++
description: یک شاخص از قاعدهٔ مشخص‌شده در مجموعه را برمی‌گرداند.
type: docs
weight: 157
url: /fa/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) متد

یک شاخص از قاعده مشخص‌شده در مجموعه را برمی‌گرداند.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | نام فونت برای جستجو. |

### مقدار بازگشتی

شاخص یک فونت یا -1 اگر فونت در لیست یافت نشود.

```cpp
// یک قاعده ایجاد می‌کند که شامل فهرستی از قلم‌ها است.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// شاخص Tahoma را دریافت می‌کند.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## توضیحات

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [FontFallBackRule](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)