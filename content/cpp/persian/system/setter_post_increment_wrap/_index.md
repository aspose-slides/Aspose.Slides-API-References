---
title: setter_post_increment_wrap()
second_title: Aspose.Slides برای مرجع API C++
description: مترجم عبارات post-increment زبان C# که به ویژگی کلاس با setter و getter تعریف شده هدف می‌گیرند، را به فراخوانی این تابع تبدیل می‌کند.
type: docs
weight: 2848
url: /fa/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) تابع

مترجم عبارات post-increment زبان C# که به ویژگی یک کلاس که setter و getter تعریف شده دارد، را به فراخوانی این تابع تبدیل می‌کند.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pGetter | T(*)() | اشاره‌گر تابعی که به تابع getter ویژگی اشاره می‌کند |
| pSetter | void(*)(T) | اشاره‌گر تابعی که به تابع setter ویژگی اشاره می‌کند |

### مقدار بازگشت

مقدار ویژگی قبل از افزایش

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) تابع

مترجم عبارات post-increment زبان C# که به ویژگی نمونه‌ای که setter و getter تعریف شده دارد، را به فراخوانی این تابع تبدیل می‌کند (بارگذاری برای getter غیر-ثابت).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی |
| Host | - کلاس نمونه‌ای که باید تغییر داده شود |
| HostGet | - Host خود یا نوع پایهٔ آن که getter ویژگی در آن تعریف شده است |
| HostSet | - Host خود یا نوع پایهٔ آن که setter ویژگی در آن تعریف شده است |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | Host *const | نمونه‌ای که getter و setter برای آن فراخوانی می‌شود. |
| pGetter | T(HostGet::*)() | اشاره‌گر تابعی که به تابع getter ویژگی اشاره می‌کند |
| pSetter | void(HostSet::*)(T) | اشاره‌گر تابعی که به تابع setter ویژگی اشاره می‌کند |

### مقدار بازگشت

مقدار ویژگی قبل از افزایش

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) تابع

مترجم عبارات post-increment زبان C# که به ویژگی نمونه‌ای که setter و getter تعریف شده دارد، را به فراخوانی این تابع تبدیل می‌کند (بارگذاری برای getter ثابت).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع ویژگی |
| Host | - کلاس نمونه‌ای که باید تغییر داده شود |
| HostConstGet | - Host خود یا نوع پایهٔ آن که getter ویژگی در آن تعریف شده است |
| HostSet | - Host خود یا نوع پایهٔ آن که setter ویژگی در آن تعریف شده است |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| host | Host *const | نمونه‌ای که getter و setter برای آن فراخوانی می‌شود. |
| pGetter | T(HostConstGet::*)() const | اشاره‌گر تابعی که به تابع getter ویژگی اشاره می‌کند |
| pSetter | void(HostSet::*)(T) | اشاره‌گر تابعی که به تابع setter ویژگی اشاره می‌کند |

### مقدار بازگشت

مقدار ویژگی قبل از افزایش

## نگاه کنید به

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)