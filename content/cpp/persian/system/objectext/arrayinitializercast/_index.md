---
title: ArrayInitializerCast()
second_title: مرجع API Aspose.Slides برای C++
description: مقادیر بنیادی آرایه را تبدیل می‌کند (که C# به‌طور ضمنی انجام می‌دهد اما به‌نظر می‌رسد C++ این کار را نمی‌کند).
type: docs
weight: 209
url: /fa/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) متد

مقادیر بنیادی آرایه را تبدیل می‌کند (که C# به‌طور ضمنی انجام می‌دهد اما به‌نظر می‌رسد C++ این کار را نمی‌کند).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| To | نوع مقصد. |
| From | نوع‌های منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| args | From ... | مقادیر برای تبدیل و افزودن به آرایه هدف. |

### مقدار برگشتی

[Array](../../array/) شامل نسخه‌های تبدیل‌شدهٔ تمام آرگومان‌ها به همان ترتیب.

## موارد مرتبط

* کلاس [ObjectExt](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)