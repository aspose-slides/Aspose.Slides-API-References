---
title: Remove()
second_title: Aspose.Slides برای C++ مرجع API
description: اولین رخداد یک فونت FallBack خاص را از فهرست حذف می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) متد


اولین رخداد یک فونت FallBack خاص را از فهرست حذف می‌کند.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | نام فونت برای حذف از لیست. |
## توضیحات



```cpp
// یک قانون ایجاد می‌کند که شامل فهرستی از قلم‌ها است.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tahoma را از فهرست حذف می‌کند.
newRule->Remove(u"Tahoma");
```


## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [FontFallBackRule](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)