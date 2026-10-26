---
title: AddFallBackFonts()
second_title: مرجع API Aspose.Slides برای C++
description: قلم(ها)ی جدیدی را به فهرست قلم‌های FallBack اضافه می‌کند.
type: docs
weight: 79
url: /fa/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) متد

یک یا چند قلم جدید را به فهرست قلم‌های FallBack اضافه می‌کند.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | نام یا نام‌های قلم (جدا شده با کاما) برای FallBack |

## توضیحات

```cpp
// ایجاد یک نمونه جدید از FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//افزودن یک قلم دوم به قانون
newRule->AddFallBackFonts(u"MS Gothic");
//افزودن قلم‌های سوم و چهارم به قانون
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) متد

قلم‌های جدیدی را به فهرست قلم‌های FallBack اضافه می‌کند.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | نام یا نام‌های قلم (جدا شده با کاما) برای FallBack |

## توضیحات

```cpp
//ایجاد نمونه جدید از FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//افزودن سه قلم دیگر به قانون
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [FontFallBackRule](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)