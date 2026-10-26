---
title: setter_post_decrement_wrap()
second_title: مرجع API Aspose.Slides برای C++
description: مترجم عبارات post-decrement زبان C# را که هدفشان ویژگی کلاس با setter و getter تعریف‌شده است، به فراخوانی این تابع تبدیل می‌کند.
type: docs
weight: 2874
url: /fa/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) تابع

مترجم عبارات post-decrement زبان C# را که هدفشان ویژگی کلاس با setter و getter تعریف‌شده است، به فراخوانی این تابع تبدیل می‌کند.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pGetter | T(*)() | اشارگر تابعی که به تابع آزاد getter ویژگی اشاره می‌کند |
| pSetter | void(*)(T) | اشارگر تابعی که به تابع آزاد setter ویژگی اشاره می‌کند |

### مقدار بازگشتی

مقدار ویژگی قبل از افزایش

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) تابع

مترجم عبارات post-decrement زبان C# را که هدفشان ویژگی نمونه‌ای با setter و getter تعریف‌شده است، به فراخوانی این تابع تبدیل می‌کند (بارگذاری برای getter غیر-ثابت).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی. |
| Host | - کلاس نمونه‌ای که باید تغییر داده شود |
| HostGet | - خود Host یا نوع پایهٔ آن که getter ویژگی در آن تعریف شده است |
| HostSet | - خود Host یا نوع پایهٔ آن که setter ویژگی در آن تعریف شده است |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | Host *const | نمونه‌ای که getterها و setterها برای آن فراخوانی می‌شوند. |
| pGetter | T(HostGet::*)() | اشارگر تابعی که به تابع getter ویژگی اشاره می‌کند |
| pSetter | void(HostSet::*)(T) | اشارگر تابعی که به تابع setter ویژگی اشاره می‌کند |

### مقدار بازگشتی

مقدار ویژگی قبل از افزایش

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) تابع

مترجم عبارات post-decrement زبان C# را که هدفشان ویژگی نمونه‌ای با setter و getter تعریف‌شده است، به فراخوانی این تابع تبدیل می‌کند (بارگذاری برای getter ثابت).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی. |
| Host | - کلاس نمونه‌ای که باید تغییر داده شود |
| HostConstGet | - خود Host یا نوع پایهٔ آن که getter ویژگی در آن تعریف شده است |
| HostSet | - خود Host یا نوع پایهٔ آن که setter ویژگی در آن تعریف شده است |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | Host *const | نمونه‌ای که getterها و setterها برای آن فراخوانی می‌شوند. |
| pGetter | T(HostConstGet::*)() const | اشارگر تابعی که به تابع getter ویژگی اشاره می‌کند |
| pSetter | void(HostSet::*)(T) | اشارگر تابعی که به تابع setter ویژگی اشاره می‌کند |

### مقدار بازگشتی

مقدار ویژگی قبل از افزایش

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)