---
title: FontFallBackRule()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید ایجاد می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) سازنده

یک نمونه جدید ایجاد می‌کند.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | **uint32_t** | شاخص شروع محدوده یونیکد |
| endIndex | **uint32_t** | شاخص پایان محدوده یونیکد |
| fontNames | [System::String](../../../system/string/) | نام یا نام‌های قلم (جدا شده با کاما) برای FallBack |

## توضیحات

```cpp
// یک نمونه جدید از FantFallBackRule با یک قلم ایجاد می‌کند.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// یک نمونه جدید از FantFallBackRule با چند قلم ایجاد می‌کند.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) سازنده

یک نمونه جدید ایجاد می‌کند.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | **uint32_t** | شاخص شروع محدوده یونیکد |
| endIndex | **uint32_t** | شاخص پایان محدوده یونیکد |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | نام یا نام‌های قلم (جدا شده با کاما) برای FallBack |

## توضیحات

```cpp
// یک نمونه جدید از FantFallBackRule با دو قلم ایجاد می‌کند
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// یک نمونه جدید از FantFallBackRule با چند قلم ایجاد می‌کند.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [FontFallBackRule](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)