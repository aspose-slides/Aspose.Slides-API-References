---
title: RemoveAt()
second_title: Aspose.Slides برای C++ مرجع API
description: قلم FallBack را در ایندکس مشخص‌شده از لیست حذف می‌کند.
type: docs
weight: 92
url: /fa/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) متد

قلم FallBack را در ایندکس مشخص شده از لیست حذف می‌کند.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرپایه قلم برای حذف. |
## توضیحات


```cpp
// قاعده‌ای که شامل فهرستی از قلم‌ها است ایجاد می‌کند.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//حذف Tahoma از فهرست
newRule->RemoveAt(2);
```


## موارد مرتبط

* کلاس [IFontFallBackRule](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)