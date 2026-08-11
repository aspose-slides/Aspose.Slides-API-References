---
title: setter_wrap()
second_title: Aspose.Slides برای مرجع API C++
description: بارگذاری برای توابع setter ایستا با تبدیل نوع.
type: docs
weight: 2822
url: /fa/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) تابع

بارگذاری برای توابع setter ایستا با تبدیل نوع.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### پارامترهای قالب

| پارامتر | شرح |
| --- | --- |
| T | نوع مقدار. |
| T2 | نوع مورد انتظار توسط تابع setter. |

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| pSetter | void(*)(T2) | مرجع تابع setter ایستا. |
| value | T | مقداری برای تنظیم. |

### مقدار برگشتی

مقدار را تنظیم می‌کند.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) تابع

بارگذاری برای توابع setter نمونه‌ای با تبدیل نوع.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### پارامترهای قالب

| پارامتر | شرح |
| --- | --- |
| T | نوع مقدار. |
| T2 | نوع مورد انتظار توسط تابع setter. |
| Host | نوع نمونه. |
| HostSet | - Host خود، یا نوع پایه آن، که setter ویژگی در آن تعریف شده است. |

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| host | Host *const | [Object](../object/) برای فراخوانی تابع setter. |
| pSetter | void(HostSet::*)(T2) | مرجع تابع setter. |
| value | T | مقداری برای تنظیم. |

### مقدار برگشتی

مقدار را تنظیم می‌کند.

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)