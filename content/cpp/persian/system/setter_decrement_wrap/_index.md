---
title: setter_decrement_wrap()
second_title: Aspose.Slides برای C++ مرجع API
description: مترجم عبارات پیش‌کاهش C# که هدفشان ویژگی کلاس با setter و getter تعریف‌شده است، به فراخوانی این تابع تبدیل می‌کند.
type: docs
weight: 2861
url: /fa/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) تابع

مترجم عبارات پیش‌کاهش C# که به ویژگی کلاس با setter و getter تعریف‌شده هدف هستند را به فراخوانی این تابع تبدیل می‌کند.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pGetter | T(*)() | اشاره‌گر تابع به تابع آزاد getter ویژگی |
| pSetter | void(*)(T) | اشاره‌گر تابع به تابع آزاد setter ویژگی |

### مقدار بازگشتی

مقدار ویژگی قبل از افزایش

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) تابع

مترجم عبارات پیش‌کاهش C# که به ویژگی نمونه با setter و getter تعریف‌شده هدف هستند را به فراخوانی این تابع تبدیل می‌کند (بارگذاری برای getter غیر-ثابت).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی. |
| Host | - کلاس نمونه‌ای که باید تغییر یابد |
| HostGet | - خود Host یا نوع پایه‌ای آن که getter ویژگی در آن تعریف شده است |
| HostSet | - خود Host یا نوع پایه‌ای آن که setter ویژگی در آن تعریف شده است |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | Host *const | نمونه‌ای که getter و setter برای آن فراخوانی می‌شود. |
| pGetter | T(HostGet::*)() | اشاره‌گر تابع به تابع getter ویژگی |
| pSetter | void(HostSet::*)(T) | اشاره‌گر تابع به تابع setter ویژگی |

### مقدار بازگشتی

مقدار ویژگی قبل از افزایش

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) تابع

مترجم عبارات پیش‌کاهش C# که به ویژگی نمونه با setter و getter تعریف‌شده هدف هستند را به فراخوانی این تابع تبدیل می‌کند (بارگذاری برای getter ثابت).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی. |
| Host | - کلاس نمونه‌ای که باید تغییر یابد |
| HostConstGet | - خود Host یا نوع پایه‌ای آن که getter ویژگی در آن تعریف شده است |
| HostSet | - خود Host یا نوع پایه‌ای آن که setter ویژگی در آن تعریف شده است |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | Host *const | نمونه‌ای که getter و setter برای آن فراخوانی می‌شود. |
| pGetter | T(HostConstGet::*)() const | اشاره‌گر تابع به تابع getter ویژگی |
| pSetter | void(HostSet::*)(T) | اشاره‌گر تابع به تابع setter ویژگی |

### مقدار بازگشتی

مقدار ویژگی قبل از افزایش

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)