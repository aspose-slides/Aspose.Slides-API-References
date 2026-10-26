---
title: Remove()
second_title: Aspose.Slides برای C++ مرجع API
description: اولین رخداد یک قلم FallBack خاص را از فهرست حذف می‌کند.
type: docs
weight: 79
url: /fa/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) متد

اولین رخداد یک قلم FallBack خاص را از فهرست حذف می‌کند.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | نام قلمی که باید از فهرست حذف شود. |

## توضیحات

```cpp
// یک قاعده ایجاد می‌کند که شامل لیستی از قلم‌ها است.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// حذف Tahoma از لیست
newRule->Remove(u"Tahoma");
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [IFontFallBackRule](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)