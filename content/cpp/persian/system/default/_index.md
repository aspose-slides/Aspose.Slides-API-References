---
title: Default()
second_title: Aspose.Slides برای مرجع API C++
description: مرجع نمونهٔ تک‌بار ساخته‌شده به‌صورت پیش‌فرض از نوع استثنا را برمی‌گرداند.
type: docs
weight: 2224
url: /fa/system/default/
---
## System::Default() تابع

مرجع نمونهٔ تک‌بار ساخته‌شده به‌صورت پیش‌فرض از نوع استثنا را برمی‌گرداند.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی که نمونهٔ آن برگردانده می‌شود |

## System::Default() تابع

مرجع نمونهٔ تک‌بار ساخته‌شده به‌صورت پیش‌فرض از نوع غیراستثنا را برمی‌گرداند.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوعی که نمونهٔ آن برگردانده می‌شود |

## موارد مرتبط

* ساختار [IsExceptionWrapper](../isexceptionwrapper/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)