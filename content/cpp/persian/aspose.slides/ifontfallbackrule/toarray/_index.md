---
title: ToArray()
second_title: Aspose.Slides برای مرجع API زبان C++
description: آرایه‌ای شامل تمام قلم‌های FallBack برای این قانون ایجاد می‌کند و برمی‌گرداند.
type: docs
weight: 105
url: /fa/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() متد

یک آرایه شامل تمام قلم‌های FallBack برای این قانون ایجاد می‌کند و برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### مقدار بازگشت

آرایه‌ای از [System::String](../../../system/string/)
## توضیحات

```cpp
// یک قانون شامل فهرستی از قلم‌ها ایجاد می‌کند.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// تمام نام‌های قلم‌ها را به صورت آرایه دریافت می‌کند.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) متد

یک آرایه شامل تمام قلم‌های FallBack از محدودهٔ مشخص‌شده در لیست ایجاد می‌کند و برمی‌گرداند.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | **int32_t** | ایندکسی از اولین قلم برای افزودن. |
| count | **int32_t** | تعداد قلم‌های برای افزودن. |

### مقدار بازگشت

آرایه‌ای از [System::String](../../../system/string/)
## توضیحات

```cpp
// یک قانون شامل فهرستی از قلم‌ها ایجاد می‌کند.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// دو نام قلم آخر را به صورت آرایه دریافت می‌کند
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## مراجع مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)