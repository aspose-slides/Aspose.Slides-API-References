---
title: AddFallBackFonts()
second_title: Aspose.Slides برای مرجع API C++
description: یک یا چند فونت جدید را به فهرست فونت‌های FallBack اضافه می‌کند.
type: docs
weight: 40
url: /fa/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) متد

یک یا چند فونت جدید را به فهرست فونت‌های FallBack اضافه می‌کند.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | نام یا نام‌های فونت (جدا شده با کاما) برای FallBack |
## توضیحات

```cpp
//ایجاد یک نمونه جدید از FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//افزودن یک فونت دوم به قانون
newRule->AddFallBackFonts(u"MS Gothic");
//افزودن فونت‌های سوم و چهارم به قانون
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) متد

یک یا چند فونت جدید را به فهرست فونت‌های FallBack اضافه می‌کند.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | نام یا نام‌های فونت (جدا شده با کاما) برای FallBack |
## توضیحات

```cpp
//ایجاد یک نمونه جدید از FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//افزودن سه فونت دیگر به قانون
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## مراجع

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [IFontFallBackRule](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)