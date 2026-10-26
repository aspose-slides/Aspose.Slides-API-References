---
title: PrintToString()
second_title: Aspose.Slides برای C++ مرجع API
description: شی را به رشته تبدیل می‌کند با انتخاب تابع سریالایزر مناسب.
type: docs
weight: 1
url: /fa/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) تابع

‏شی را به رشته تبدیل می‌کند با انتخاب تابع سریالایزر مناسب.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | [Object](../../system/object/) نوع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) برای چاپ. |

### مقدار بازگشت

[String](../../system/string/) نمایش‌های شی عبور داده‌شده.

## System::TestPredicates::Details::PrintToString(const T\&) تابع

‏کانتینرهای سبک ICollection را به رشته تبدیل می‌کند با چاپ عناصرشان (بیش از 32 عنصر چاپ نمی‌شود).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | [Object](../../system/object/) نوع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) برای چاپ. |

### مقدار بازگشت

نمایش‌های رشته‌ای ترکیبی عناصر موجود.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) تابع

‏nullptr را به رشته تبدیل می‌کند.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### مقدار بازگشت

رشته "nullptr".

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) تابع

[IEnumerable<bool>](../../system.collections.generic/ienumerable/) کالکشن‌ها را به رشته تبدیل می‌کند با چاپ عناصرشان (بیش از 32 عنصر چاپ نمی‌شود).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | [Object](../../system/object/) نوع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) برای چاپ. |

### مقدار بازگشت

نمایش‌های رشته‌ای ترکیبی عناصر موجود.

## مراجع

* کلاس [IEnumerable](../../system.collections.generic/ienumerable/)
* ساختار [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* فضای نام [System::TestPredicates::Details](../)
* کتابخانه [Aspose.Slides](../../)